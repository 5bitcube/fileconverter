# fileconverter
A simple bash script that converts between different file formats.

<h2>1.0 Introduction</h2>
This basic script allows the user to quickly convert between different file formats by adding a custom entry to the context menu on Linux's Dolphin file manager.
For a more detailed tutorial on how to set this up, read <a href="https://5bitcube.com/articles.php?q=how-to-add-custom-options-to-the-context-menu-on-linux">this article</a>.

<h2>2.0 How To Install</h2>
<b>Step 1:</b> <i>sudo apt-get install imagemagick</i><br/>
<b>Step 2:</b> <i>sudo apt-get install ffmpeg</i><br/>
<b>Step 3:</b> Copy "<a href="https://github.com/5bitcube/fileconverter/releases/download/v1.0.0/fileconverter">fileconverter</a>" into your scripts folder.<br/>
<b>Step 4:</b> Copy "<a href="https://github.com/5bitcube/fileconverter/releases/download/v1.0.0/fileconverter.desktop">fileconverter.desktop</a>" into "/home/USERNAME/.local/share/kservices5/ServiceMenus/".<br/>

<h2>3.0 Supported Extensions</h2>
<h3>[Source File]</h3>
PNG, WEBP, JPEG, JPG
<h3>[Output File]</h3>
JPG, MP4

<h2>4.0 How To Use</h2>
Right-click any file or group of files from the <i>supported extensions</i>, then run "Actions > Convert To > [Target Extension]".

<h3>4.1 JPG</h3>
When converting to JPG, you will be asked to select the output file quality from the terminal.

<h3>4.2 MP4</h3>
In order to convert several image files into MP4 videos of different lengths, you may provide a "subs.srt" file on the same folder as your selected images. This SRT file must be properly formatted with timestamp entries in the form: 00:00:17,620 --> 00:00:21,270
