# jquery-fontscaler
jQuery plugin which scales the font-size of an element to fit given a maximum number of lines.

### Version 0.1
This is basically untested and is for reference only. The text width calculation is based on this solution from stack: https://stackoverflow.com/a/18109656

### How To:
See the demo. **TLDR:** call .fontScale() on each object you want to scale the font, set a data-maxlines="2" or whatever you want the maximum lines for the container to be, the script will try and get you about 1.5 lines of text after scaling. The calculation is a bit fuzzy as it doesn't take into account word breaks at the moment.
