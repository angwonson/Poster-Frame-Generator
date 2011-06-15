Poster Frame Generator (AS3)

Poster Frame Generator is a simple implementation of FLVPlayback object which allows CMS authors and video sharing sites to provide a simple and easy way to capture that all important poster frame image.

This is almost completely based on http://marstonstudio.com/2007/10/19/how-to-take-a-snapshot-of-a-flash-movie-and-automatically-upload-the-jpg-to-a-server-in-three-easy-steps/


INSTALLATION

To install this utility, simply copy the swf file to your server and add the example OBJECT tag to your HTML code.


EXAMPLE

<object classid="clsid:d27cdb6e-ae6d-11cf-96b8-444553540000" width="640" height="824" id="newscreengrabber2" align="middle">
        <param name="movie" value="newscreengrabber2.swf" />
        <param name="quality" value="high" />
        <param name="bgcolor" value="#ffffff" />
        <param name="play" value="true" />
        <param name="loop" value="true" />
        <param name="wmode" value="window" />
        <param name="scale" value="showall" />
        <param name="menu" value="true" />
        <param name="devicefont" value="false" />
        <param name="salign" value="" />
        <param name="allowScriptAccess" value="sameDomain" />
        <param name="flashvars" value="video_id=1234&video_file=https://www.masonqm.com/cms/media/playvideo/1234.flv" />
        <!--[if !IE]>-->
        <object type="application/x-shockwave-flash" data="newscreengrabber2.swf" width="640" height="824">
                <param name="movie" value="newscreengrabber2.swf" />
                <param name="quality" value="high" />
                <param name="bgcolor" value="#ffffff" />
                <param name="play" value="true" />
                <param name="loop" value="true" />
                <param name="wmode" value="window" />
                <param name="scale" value="showall" />
                <param name="menu" value="true" />
                <param name="devicefont" value="false" />
                <param name="salign" value="" />
                <param name="allowScriptAccess" value="sameDomain" />
				<param name="flashvars" value="video_id=1234&video_file=https://www.masonqm.com/cms/media/playvideo/1234.flv" />
        <!--<![endif]-->
                <a href="http://www.adobe.com/go/getflash">
                        <img src="http://www.adobe.com/images/shared/download_buttons/get_flash_player.gif" alt="Get Adobe Flash player" />
                </a>
        <!--[if !IE]>-->
        </object>
        <!--<![endif]-->
</object>


SUPPORT AND DOCUMENTATION

After installing, you can find documentation for this module on the masonqm website.

You can also look for source code and developer information at:

    GITHUB
	https://github.com/masonqm/Poster-Frame-Generator


TODO

- Add flashvars option to modify the POST url
- Add flashvar option to turn sounds off


INSPIRATION

http://marstonstudio.com/2007/10/19/how-to-take-a-snapshot-of-a-flash-movie-and-automatically-upload-the-jpg-to-a-server-in-three-easy-steps/
http://henryjones.us/articles/using-the-as3-jpeg-encoder
http://www.bytearray.org/?p=26


LICENSE AND COPYRIGHT

Copyright (C) 2011 Chris Fulton

This program is free software; you can redistribute it and/or modify it
under the terms of either: the GNU General Public License as published
by the Free Software Foundation; or the Artistic License.

See http://dev.perl.org/licenses/ for more information.


ADDITIONAL LICENSES AND COPYRIGHTS

com.adobe.images.JPGEncoder is Copyright (c) 2008, Adobe Systems Incorporated and redistributed under the license agreement in the license.txt file in that folder.

UploadPostHelper Copyright 2007 Jonathan Marston and distributed under the Creative Commons license:
http://creativecommons.org/licenses/by-nc-sa/3.0/

3 sound effects are provided by freesounds.org under their license terms: http://www.freesound.org/legal.php http://creativecommons.org/licenses/sampling+/1.0/legalcode
