# Max Patches for the 2018 version of my piece/system Neither Time Nor Energy (Bowed Cardboard Box and Truculent Electronics)

This version has been performed at Electric Spring, 2018, Huddersfield, UK ([video](https://www.youtube.com/watch?v=VExDlHD7o80)); and the ERC, European Research Music Conference 2018, UPF, Barcelona (see [here](https://eventum.upf.edu/19834/section/12361/european-research-music-conference.html)). 

## Dependencies 

Max 7 (or 8, depending on the below), and the following

* [Framelib](https://github.com/AlexHarker/FrameLib/)
* [Aharker externals](https://github.com/AlexHarker/AHarker_Externals) (specifically the objects `descriptorsrt~`, `meandev`)

These are available via the Max Package Manager: 
* Jasch  
* Xray
* Bach

## Broad idea
The original version of this came together at the start of 2015, alongside a collaboration with Martin Parker on a installation called *Limits to Growth*. Both used the same underlying code, though this has diverged in the meantime.

The idea in each case was to combine a (semi-)autonomous, machine-listening driven system with a pool of pre-composed gestures (for these purposes, temporal patterns of parameter changes on particular processes), to try and navigate territory between something whose sonic character was determined wholly in the moment, and something that had recognisable, and recurring motifs that would imbue the system-piece with a recognisable and deliberate sense of identity.  

## Can I Play This? 
Uh, you're welcome to try. But be warned, it's currently in that special gig-scarred state of being hard to follow, held together by principles that are documented only in my head, and somewhat temperamental. It's probably somewhat overfitted to my box playing as well. In principle, most of the temporal behaviour of the thing can be changed, but realistically this is off-puttingly fiddly and brittle at the moment. 

On which note: 

## The Most Urgent TODOs 
* [ ] Make clearer and properly document control / signal flow 
* [ ] Strip out `pattrstorage` (sometimes unreliable with loading files; can buckle under heavy message load)
* [ ] Make it much easier to define new gesture shapes and experiment with them (with a longer term view to developing a more principled way to tune the relationship between pre-defined and machine-listened controls) 
* [ ] Introduce some global mechanism for tuning / modulating system sensitivity in machine listening bits 
* [ ] Factor out custom externals into dedicated repos 
