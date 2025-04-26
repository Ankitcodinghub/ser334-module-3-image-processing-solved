# ser334-module-3-image-processing-solved
**TO GET THIS SOLUTION VISIT:** [SER334 Module 3-Image Processing Solved](https://www.ankitcodinghub.com/product/ser334-module-3-image-processing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;62673&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SER334 Module 3-Image Processing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Summary: In this homework, you will be implementing a program that loads an image le, applies a simple lter to it, and saves it back to disk. You will also learn how to read and write real-world binary le formats, speci cally BMP and PPM.

<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Background</h1>
In this assignment you will write a program that applies a&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; lter to an image. The image will be loaded from a local BMP or PPM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le, speci ed by the user, and then be transformed using a color shift also speci ed by the user. The resulting&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le will be saved back to a BMP or PPM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le that can be viewed on the host system.

This document is separated into four sections: Background, Requirements, Loading Binary Files, Include Files, and Submission. You have almost nished reading the Background section already. In Requirements, we will discuss what is expected of you in this homework. In Loading Binary Files, we will discuss the BMP and PPM le formats and how to interact with binary les. Lastly, Submission discusses how your source code should be submitted on Canvas.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Requirements [36 points]</h1>
Your program needs to implement loading a binary BMP or PPM le, applying a color shift to its pixel data, and saving the modi ed image back into a BMP or PPM le. The width and height may be of any size, but you can assume that you will be capable of storing the image data in memory. Assume that all BMP les are 24-bit uncompressed les<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> (i.e., compression method is BI_RGB), which have a 14-bit bmp header, a 40-bit dib header, and a variable length pixel array. This is shown in Figure 2. PPM les will also be in 24-bit. For testing, please only use the PPM and BMP les attached to the assignment.

As a base requirement, your program must compile and run under Xubuntu (or another variant of Ubuntu) 18.04. Sample output for this program is shown in Figure 1.

<ul>
<li>Speci c Requirements:</li>
</ul>
BMP Headers IO: Create structures for the headers of a BMP le (BMP header struct and DIB header struct) and functions which read and write them. [4 Points]

PPM Headers IO: Create structures for the headers of a PPM le (PPM header struct) and functions which read and write them. [4 Points]

Pixel IO: Create a structure which represents a single pixel (24-bit pixel struct) and the functions for reading and writing all pixels in both PPM and BMP les. [4 Point]

Input and output le names: Read the input le name and output le name from the command line arguments. The user should be required to enter the input le name and this should be the rst argument. The output le name is an option, it is not required and it can be in any place in the option list. The output le option is speci ed by -o followed by the output le name. Validate that the input le exists and that both les are of the correct type (either bmp or ppm).

[4 Points]

∗ The input&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le is the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le to read and copy.

∗ The output&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le name is the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le to write to and copy to (the new&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le created).

RGB Color Shift input: Accept options for red, green, or blue color shift. These are speci ed by -r -g or -b followed by an integer. Validate that these are integers. Like the -o option described above, these can come in any order in the option list and are optional for the user to enter. [4 Points]

∗ Note: -o -r -g and -b are all options. All for of these can come in any order (-r -g -n -b, for example) and none of them are required.

Copy images: Correctly copy images from a BMP&nbsp;&nbsp;&nbsp; le to a new BMP&nbsp;&nbsp; le and from a PPM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le to a new PPM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le. [4 Points]

Convert images: Correctly copy images from a BMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le to a new PPM&nbsp;&nbsp; le and from a PPM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le to a new BMP&nbsp;&nbsp; le. [4 Points]

Color Shift calculation: Shift the color of the new image before saving it, according to the options the user entered. [4 Points]

∗ Color shift refers to increasing or decreasing the color in a pixel by the speci ed amount. So, if the user entered -b -98 all of the blue values in a pixel would be decreased by 98.

∗ If no color shift option was entered for a color, do not shift it.

∗ After color shift, color should be clamped to 0 ~ 255. For example, color R = 100, shift = 200. The color R after shift should be 255 (300 clamped to 255).

Modular Programming: Use the provided header les correctly and create corresponding C les, along with a main le. You do not have to create any more header les or C les than this but you may if it helps you. Do not modify the header les given except to ll in any TODOs.[4 Points]

Figure 1 shows an example of how the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nished program should function.

Figure 1: Example of running the program with example output.

<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Loading Binary Files</h1>
<h2>3.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The BMP File Format</h2>
For reference, use the BMP speci cation on Wikipedia: <a href="https://en.wikipedia.org/wiki/BMP_file_format">https://en.wikipedia.org/wiki/BMP_ le_format. </a>In Figure 2, a graphical overview of a BMP le’s layout is shown. The layout is literally the meaning of the bits/bytes in the le starting at 0 and going to the end of the le. The rst (green) region shows the BMP header information in 14 bytes: 2 for the signature, 4 for the le size, 2 for reserved1, 2 for reserved2, and 4 for le o set. Details on each of these (such as their data format, and contents) can be found on the Wikipedia page. For example, the area labeled Signature should contain the characters BM to con rm that the le is in BMP format. The second (blue region) shows the DIP header information in 40 bytes: 4 for header size, 4 for width, 4 for height, and so on. The last region (yellow) forms a 2D array of pixels. It stores columns from left to right, but rows are inverted to be bottom to top. Note that each row of pixels in this section is padded to be a multiple of four bytes. For example, if a line contains two pixels (24-bits or 3-bytes each), then an addition 2-bytes of blank data will be appended.

Figure 2: BMP le format structure for 24-bit les without compression. Image modi ed from https://en.wikipedia.org/wiki/File:BMP leFormat.png.

Review the following struct called BMP_Header which holds the bmp header information. (You should also consider creating structs to hold the dib header, and pixel data.) Notice that the entries in BMP_Header correspond to the pieces of data listed in the le format. In general, a chunk of 8-bits should be represented as a char, a chunk of 16-bits as a short, and 32-bits as a int. (Optionally: consider using unsigned types.)

<table width="434">
<tbody>
<tr>
<td width="262">struct BMP_Header {</td>
<td width="172"></td>
</tr>
<tr>
<td width="262">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; char&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; signature [ 2 ] ;</td>
<td width="172">//ID&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; f i e l d</td>
</tr>
<tr>
<td width="262">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; size ;</td>
<td width="172">// Size&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; of&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the BMP f i l e</td>
</tr>
<tr>
<td width="262">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; short&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; reserved1 ;</td>
<td width="172">// Application&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; s p e c i f i c</td>
</tr>
<tr>
<td width="262">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; short&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; reserved2 ;</td>
<td width="172">// Application&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; s p e c i f i c</td>
</tr>
</tbody>
</table>
int&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; offset_pixel_array ;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // Offset&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; where&nbsp;&nbsp;&nbsp; the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; pixel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; array&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; can be found

};

Plan to review Example 1 on the Wikipedia page to get a feel for the contents of each of these regions. A recreated version of that image is provided as the attached test2.bmp le. A good exercise would be to view the le in a hex editor like HxD.

<h2>3.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The PPM File Format</h2>
The PPM le format is a much simpler format. For reference, please visit the o cial speci cation here: <a href="http://netpbm.sourceforge.net/doc/ppm.html">http://netpbm.sourceforge.net/doc/ppm.html.</a> The header of a PPM le consists of the signature P6 , follow by white space, the width of the le (in ASCII characters, not binary), white space, and the height of the image (in ASCII characters, not binary). After the header, there is a single white space character followed by the pixel array. The pixels are 3 bytes each, with each color being represented by a single byte. The columns are stored left to right and the rows top to bottom. Do not use the Plain PPM format that is described in the spec, use the regular one. From top to bottom, each PPM image text le consists of the following:

<ol>
<li>A “magic number” for identifying the le type. A ppm image’s magic number is the two characters “P6”. Whitespace (blanks, TABs, CRs, LFs).</li>
<li>A width, formatted as ASCII characters in decimal. Whitespace.</li>
<li>A height, again in ASCII decimal. Whitespace.</li>
<li>The maximum color value (maxval), again in ASCII decimal. Must be less than 65536 and more than zero. A single whitespace character (usually a newline).</li>
<li>A raster of height rows, in order from top to bottom. Each row consists of width pixels, in order from left to right. Each pixel is a triplet of red, green, and blue samples, in that order. Each sample is represented in pure binary by either 1 or 2 bytes. If the maxval is less than 256, it is 1 byte. Otherwise, it is 2 bytes. The most signi cant byte is rst.</li>
</ol>
Plan to review examples of PPM on PPM Wikipedia page <a href="https://en.wikipedia.org/wiki/Netpbm_format#PPM_example">(https://en.wikipedia.org/wiki/Netpbm_format#PPM_example)</a>

to get a feel for the contents of each of these regions. Some PPM header examples are available on <a href="http://paulbourke.net/dataformats/ppm/">http://paulbourke.net/dataformats/ppm/.</a> You should include all necessary information of the header in the PPM struct.

<h2>3.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Loading the BMP header</h2>
This is example of code to load the BMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le header (the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rst 14 bits). Figure 3 shows the output.

Figure 3: Output of base&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le on test2.bmp.

//sample&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; code&nbsp;&nbsp;&nbsp; to&nbsp;&nbsp;&nbsp;&nbsp; read&nbsp;&nbsp;&nbsp;&nbsp; f i r s t&nbsp;&nbsp;&nbsp; 14&nbsp;&nbsp;&nbsp;&nbsp; bytes&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; of BMP f i l e&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; format

FILE∗ f i l e = fopen (” test2 .bmp” , “rb “); struct BMP_Header header ;

//read bitmap f i l e header (14 bytes ) fread(&amp;header . signature , sizeof ( char )∗2 , 1 , f i l e ); fread(&amp;header . size , sizeof ( int ) , 1 , f i l e ); fread(&amp;header . reserved1 , sizeof ( short ) , 1 , f i l e ); fread(&amp;header . reserved2 , sizeof ( short ) , 1 , f i l e ); fread(&amp;header . offset_pixel_array , sizeof ( int ) , 1 , f i l e );

printf (” signature : %c%c\n” , header . signature [0] , header . signature [ 1 ] ) ; printf (” size : %d\n” , header . size ); printf (” reserved1 : %d\n” , header . reserved1 ); printf (” reserved2 : %d\n” , header . reserved2 );

printf (” offset_pixel_array : %d\n” , header . offset_pixel_array ); fclose ( f i l e ); The key functions here are:

<ul>
<li>FILE ∗fopen ( const char ∗filename ,&nbsp;&nbsp; const&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; char ∗mode)</li>
</ul>
This creates a new le stream. fopen is used with the rb mode to indicate we are r eading a le in b inary mode. To read a le, use the mode wb instead of rb .

<ul>
<li>size_t fread ( void ∗ptr , size_t&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; size ,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; size_t&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nitems ,&nbsp; FILE ∗stream )</li>
</ul>
For each call to fread, we give it rst a pointer to an element of struct containing the BMP header, then the number of bytes to read, the number of times to read (typically 1), and the le stream to use. Note that order of the calls to fread de ne the order in which we read data so the order must match the le layout. (There is also a function called fwrite which works in exactly the opposite manner. The rst won’t be a pointer though.)

One function not used here but which may be useful, is fseek:

<ul>
<li>int fseek&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ( FILE ∗ stream ,&nbsp;&nbsp;&nbsp; long&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; offset ,&nbsp;&nbsp; int&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; origin&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; )</li>
</ul>
The purpose of fseek is to move the reading head of the FILE object by some number of bytes. It can used to skip a number of bytes. The rst parameter to fseek is the le pointer, followed by a number of bytes to move, and an origin. For origin, SEEK_CUR is a relative repositioning while SEEK_SET is global repositioning.

The basic idea to support loading a BMP le will be to parse it by byte-byte (using fread) into a set of structs. Later, you can use fwrite to write out the contents of those structs to a le stream to save the ltered image.

<h2>3.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Creating le headers</h2>
When copying from BMP to BMP or PPM to PPM, you could easily copy the original&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le’s header into the new one. But when copying from BMP to PPM, or PPM to BMP, you will need to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ll in the header of the new le yourself. For example, you will need to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ll in the compression type, the number of color planes, etc for BMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; les. The following de nes default values you should use when creating an image. All values that are not de ned here, you should calculate based on the input image.

<ul>
<li>BMP Header:</li>
</ul>
Signature:&nbsp;&nbsp;&nbsp;&nbsp; BM

Reserved 1: 0

Reserved 2: 0

<ul>
<li>DIB Header:</li>
</ul>
Planes: 1

Compression: 0

Horizontal resolution: 3780

Vertical resolution: 3780

Color number: 0 Important color number: 0

<ul>
<li>PPM Header:</li>
</ul>
Magic Number:&nbsp;&nbsp;&nbsp;&nbsp; P6

Maximum color value:&nbsp;&nbsp;&nbsp;&nbsp; 255

<h1>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Include Files</h1>
To complete this assignment, you may&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; nd the following include&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; les and functions useful:

<ul>
<li>h: De nes standard IO functions.</li>
<li>h: De nes memory allocation functions.</li>
<li>h: De nes string manipulation functions.</li>
</ul>
char* strcat(char* dest, const char* src): The strcat() function appends the string pointed to by src to the end of the string pointed to by dest.

char* strcpy(char* dest, const char* src): The strcpy() function copies the string pointed to, by src to dest.

size_t strlen(const char* str): The strlen() function computes the length of the string str up to, but not including the terminating null character.

char* strtok_r(char* str, const char* delim, char** saveptr): The strtok_r function parses a string into a sequence of tokens.

<ul>
<li>h: De nes POSIX operating system API functions.</li>
</ul>
int getopt(int argc, char *const argv[], const char *optstring): The getopt() function is a builtin function in C and is used to parse command line arguments.

Your solution may not include all of these include les or functions, they are only suggestions. If you want to include any other les, please check with the instructor or TA before doing so. Note: Since PPM les are in ASCII (not binary), you should write and read them di erently. fprint and fscanf would be a good choice to write and read PPM les.

<a href="#_ftnref1" name="_ftn1">[1]</a> 1In case you think this is making the assignment unrealistic, think again: this is the default Windows 10 BMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; le format.
