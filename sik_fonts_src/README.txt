These are the SFD files for use with FontForge. As you can see they aren't...
made in a reasonable way for a typographer. They're made at a low resolution
and relying a lot on overlapping.

To generate the TTF files, make a copy of the SFD file, then:

- Change em size to 1024 (let it scale everything accordingly)
- Select all, remove overlaps
- Select all, generate hints

And then generate the TTF file. Or whatever format you prefer to use.

NOTE: Video Glau is quite buggy with some of the arrows due to serious
overlap abuse... that's something to be fixed in the future.
