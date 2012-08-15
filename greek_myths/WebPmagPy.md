<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"  
  "http://www.w3.org/TR/html4/loose.dtd">  
<html > 
<head><title>PmagPy Cookbook</title> 
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1"> 
<meta name="generator" content="TeX4ht (http://www.cse.ohio-state.edu/~gurari/TeX4ht/)"> 
<meta name="originator" content="TeX4ht (http://www.cse.ohio-state.edu/~gurari/TeX4ht/)"> 
<!-- html,1,sections+ --> 
<meta name="src" content="WebPmagPy.tex"> 
<meta name="date" content="2012-07-10 18:32:00"> 
<link rel="stylesheet" type="text/css" href="WebPmagPy.css"> 
</head><body 
>
<!--l. 56--><p class="noindent" >July 10, 2012    <div class="maketitle">
                                                                              

                                                                              
                                                                              

                                                                              
                                                                              

                                                                              

<h2 class="titleHead">PmagPy Cookbook</h2>
            <div class="author" ><span 
class="cmr-12">Lisa Tauxe</span>
<br /><span 
class="cmr-12">Scripps Institution of Oceanography</span>
<br />      <span 
class="cmr-12">La Jolla, CA 92093-0220</span></div><br />
<div class="date" ><span 
class="cmr-12">July 10, 2012</span></div>
                                                                              

                                                                              
   </div>
                                                                              

                                                                              
   <div class="tableofcontents">
   <span class="likechapterToc" ><a 
href="#x1-1000" id="QQ2-1-1">Contents</a></span>
   </div>
   <h2 class="likechapterHead"><a 
href="#QQ2-1-1" id="x1-1000">Contents</a></h2> <div class="tableofcontents">
   &#x00A0;<span class="sectionToc" >0.1 <a 
href="#x1-20000.1" id="QQ2-1-2">The <span 
class="cmbx-10x-x-109">PmagPy </span>software package</a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.1.1 <a 
href="#x1-30000.1.1" id="QQ2-1-3">Downloading and installing PmagPy</a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.1.2 <a 
href="#x1-40000.1.2" id="QQ2-1-4">General characteristics of PmagPy programs</a></span>
<br />   &#x00A0;<span class="sectionToc" >0.2 <a 
href="#x1-50000.2" id="QQ2-1-5">Examples of how to use <span 
class="cmbx-10x-x-109">PmagPy </span>programs</a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.1 <a 
href="#x1-60000.2.1" id="QQ2-1-6"><span 
class="cmbx-10x-x-109">ani</span><span 
class="cmbx-10x-x-109">_depthplot.py</span></a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.2 <a 
href="#x1-70000.2.2" id="QQ2-1-7"><span 
class="cmbx-10x-x-109">aarm</span><span 
class="cmbx-10x-x-109">_magic.py</span></a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.3 <a 
href="#x1-80000.2.3" id="QQ2-1-8"><span 
class="cmbx-10x-x-109">agm</span><span 
class="cmbx-10x-x-109">_magic.py</span></a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.4 <a 
href="#x1-90000.2.4" id="QQ2-1-9"><span 
class="cmbx-10x-x-109">angle.py </span></a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.5 <a 
href="#x1-100000.2.5" id="QQ2-1-10"><span 
class="cmbx-10x-x-109">core</span><span 
class="cmbx-10x-x-109">_depthplot.py</span></a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.6 <a 
href="#x1-110000.2.6" id="QQ2-1-11"><span 
class="cmbx-10x-x-109">dir</span><span 
class="cmbx-10x-x-109">_cart.py</span></a></span>
<br />   &#x00A0;&#x00A0;<span class="subsectionToc" >0.2.7 <a 
href="#x1-120000.2.7" id="QQ2-1-12"><span 
class="cmbx-10x-x-109">download</span><span 
class="cmbx-10x-x-109">_magic.py</span></a></span>
   </div>
<!--l. 62--><p class="noindent" ><a name='sec0-1'></a><h3 class="sectionHead"><span class="titlemark">0.1   </span> <a 
href="#QQ2-1-2" id="x1-20000.1">The <span 
class="cmbx-10x-x-109">PmagPy </span>software package</a></h3>
<!--l. 65--><p class="noindent" >The <span 
class="cmbx-10x-x-109">PmagPy </span>software package is a comprehensive set of programs for paleomagnetists and
rock magnetists. It is written in Python and the reader is encouraged to consult the Python
for Paleomagnetists website (COMING SOON TO A URL NEAR YOU) and the textbook
by Tauxe et al., 2010 available at <a 
href="http://magician.ucsd.edu/Essentials" class="url" ><span 
class="cmtt-10x-x-109">http://magician.ucsd.edu/Essentials</span></a> so that you
don&#8217;t use the programs as a &#8220;black box&#8221;.
<!--l. 67--><p class="indent" >   Here follows a brief introduction.
<!--l. 69--><p class="noindent" >
<!--l. 69--><p class="indent" >   <a name='subsec0-1-1'></a><h4 class="subsectionHead"><span class="titlemark">0.1.1   </span> <a 
href="#QQ2-1-3" id="x1-30000.1.1">Downloading and installing PmagPy</a></h4>
<!--l. 71--><p class="noindent" >You can find the most recent distribution of PmagPy by following the link to the PmagPy
home page via:
<!--l. 73--><p class="indent" >   <a 
href="http://magician.ucsd.edu/Software/PmagPy/" class="url" ><span 
class="cmtt-10x-x-109">http://magician.ucsd.edu/Software/PmagPy/</span></a>.
<!--l. 75--><p class="indent" >   Install it following the directions, especially making sure that the directory in which the
scripts is placed is in your path.
                                                                              

                                                                              
<!--l. 77--><p class="noindent" >
<!--l. 77--><p class="indent" >   <a name='subsec0-1-2'></a><h4 class="subsectionHead"><span class="titlemark">0.1.2   </span> <a 
href="#QQ2-1-4" id="x1-40000.1.2">General characteristics of PmagPy programs</a></h4>
<!--l. 79--><p class="noindent" ><span 
class="cmbx-10x-x-109">PmagPy </span>scripts work by calling them on a command line (see Section&#x00A0;<span 
class="cmbx-10x-x-109">??</span>). The python
scripts must be placed in a directory that is in your &#8220;path&#8221;. To see if this has been properly
done, type <span 
class="cmbx-10x-x-109">dir</span><span 
class="cmbx-10x-x-109">_cart.py -h </span>on the command line and you should get a help message. If
you get a &#8220;command not found&#8221; message, you need to fix your path; check the
&#8220;installing python&#8221; page on the software website. Another possible cause for failure is
that somehow, the python scripts are no longer executable. To fix this, change
directories into the directory with the scripts, and type the command: chmod a+x
*.py
<!--l. 81--><p class="indent" >   For people who hate command line programs and prefer graphical user interfaces with
menus, etc., some of the key programs for interpreting paleomagnetic and rock magnetic data
are packaged together in a program called <span 
class="cmbx-10x-x-109">MagIC.py</span>. This can be invoked by typing
<span 
class="cmbx-10x-x-109">MagIC.py </span>on the command line. The <span 
class="cmbx-10x-x-109">MagIC.py </span>program generates the desired commands
for you, so you do not have to learn UNIX or how to use the command line (except to call
the <span 
class="cmbx-10x-x-109">MagIC.py </span>program itself). Nonetheless, some understanding of what is actually
happening is helpful, because the <span 
class="cmbx-10x-x-109">MagIC.py </span>program is more limited than full range of
<span 
class="cmbx-10x-x-109">PmagPy </span>programs. So, here is a brief introduction to how the <span 
class="cmbx-10x-x-109">PmagPy </span>programs
work.
<!--l. 84--><p class="indent" >   All <span 
class="cmbx-10x-x-109">PmagPy </span>programs print a help message out if you type: <span 
class="cmbx-10x-x-109">program</span><span 
class="cmbx-10x-x-109">_name.py -h</span>
on the command line. Many have an &#8220;intereactive&#8221; option triggered by typing
<span 
class="cmbx-10x-x-109">program</span><span 
class="cmbx-10x-x-109">_name.py -i</span>. Many also allow reading from standard input and output. The help
message will explain how each particular program functions. There are some common
features for the command line options:
<!--l. 87--><p class="indent" >
     <ol  class="enumerate1" >
     <li 
  class="enumerate" id="x1-4002x1">Switches are from one to three characters long, preceded by a &#8217;-&#8217;.
     </li>
     <li 
  class="enumerate" id="x1-4004x2">The switch &#8217;-h&#8217; always prints the help message and &#8217;-i&#8217; allows interactive entry of
     options.
     </li>
     <li 
  class="enumerate" id="x1-4006x3">Options for command line switches immediately follow the switch. For example:
     -f  INPUT  -F  OUTPUT  will  set  the  input  file  to  INPUT  and  the  output  to
     OUTPUT.
     </li>
     <li 
  class="enumerate" id="x1-4008x4">The switch for input files all start with -f and -F for output files.
     </li>
     <li 
  class="enumerate" id="x1-4010x5">-spc  -sam  -sit  -syn  -loc  are  switches  relating  to  specimens,  samples,  sites,
     synthetics and locations respectively.
                                                                              

                                                                              
     </li>
     <li 
  class="enumerate" id="x1-4012x6">Capitalized switches suppress an option (e.g., -A means do not average, while -a
     means DO average).
     </li>
     <li 
  class="enumerate" id="x1-4014x7">-crd [s,g,t] sets the coordinate system
     </li>
     <li 
  class="enumerate" id="x1-4016x8">-fmt [svg,png,jpg] the default image format.
     </li>
     <li 
  class="enumerate" id="x1-4018x9">-sav saves the plots silently and quits the program</li></ol>
<!--l. 103--><p class="indent" >   The <span 
class="cmbx-10x-x-109">PmagPy </span>scripts call on two special modules, the <span 
class="cmbx-10x-x-109">pmag </span>and the <span 
class="cmbx-10x-x-109">pmagplotlib</span>
modules. These contain most of the calculations and plotting functions.
<!--l. 105--><p class="noindent" >
<!--l. 105--><p class="indent" >   <a name='sec0-2'></a><h3 class="sectionHead"><span class="titlemark">0.2   </span> <a 
href="#QQ2-1-5" id="x1-50000.2">Examples of how to use <span 
class="cmbx-10x-x-109">PmagPy </span>programs</a></h3>
<!--l. 108--><p class="noindent" >In all examples, the &#8217;%&#8217; prompt stands for whatever command line prompt you have.
Download the package containing example data files for this book from:
<!--l. 111--><p class="indent" >
<!--l. 111--><p class="noindent" ><a 
href="http://magician.ucsd.edu/Software/PmagPy/Datafiles.zip" class="url" ><span 
class="cmtt-10x-x-109">http://magician.ucsd.edu/Software/PmagPy/Datafiles.zip</span></a>
<!--l. 113--><p class="noindent" >and unzip the file. Data files for the following examples can be found in the <span 
class="cmti-10x-x-109">Examples</span>
directory.
<!--l. 115--><p class="noindent" ><a name='ani_depthplot.py'></a>
<!--l. 116--><p class="noindent" ><a name='subsec0-2-1'></a><h4 class="subsectionHead"><span class="titlemark">0.2.1   </span> <a 
href="#QQ2-1-6" id="x1-60000.2.1"><span 
class="cmbx-10x-x-109">ani</span><span 
class="cmbx-10x-x-109">_depthplot.py</span></a></h4>
<!--l. 117--><p class="noindent" >[<a 
href="http://webbookcopy.html#paleomagnetic_tensors" >Chapter 13</a>; <a 
href="http://earthref.org/MAGIC/" >MagIC database</a>]
<!--l. 121--><p class="noindent" >Anisotropy data can be plotted versus depth. The program <span 
class="cmbx-10x-x-109">ani</span><span 
class="cmbx-10x-x-109">_depthplot.py </span>uses
MagIC formatted data tables of the <span 
class="cmti-10x-x-109">rmag</span><span 
class="cmti-10x-x-109">_anisotropy.txt </span>and <span 
class="cmti-10x-x-109">er</span><span 
class="cmti-10x-x-109">_samples.txt </span>types.
<span 
class="cmti-10x-x-109">rmag</span><span 
class="cmti-10x-x-109">_anisotropy.txt </span>stores the tensor elements and measurement meta-data while
<span 
class="cmti-10x-x-109">er</span><span 
class="cmti-10x-x-109">_samples.txt </span>stores the depths, location and other information. Bulk susceptibility
measurements can also be plotted if they are available in a <span 
class="cmti-10x-x-109">magic</span><span 
class="cmti-10x-x-109">_measurements.txt</span>
formatted file.
<!--l. 123--><p class="noindent" >In this example, we will use the data from Tauxe et al. (2012) measured on samples obtained
during Expedition 318 of the International Ocean Drilling Program. To get the entire
dataset, go to the MagIC data base at: <a 
href="http://earthref.org/MAGIC/" class="url" ><span 
class="cmtt-10x-x-109">http://earthref.org/MAGIC/</span></a> and find the data
using the search interface. As a short-cut, you can use the &#8220;permalink&#8221;:
<!--l. 126--><p class="noindent" ><a 
href="http://earthref.org/MAGIC/m000629dt20120607193954" class="url" ><span 
class="cmtt-10x-x-109">http://earthref.org/MAGIC/m000629dt20120607193954</span></a>.
<!--l. 128--><p class="noindent" >Download the text file by clicking on the icon under the red arrow in:
                                                                              

                                                                              
<!--l. 130--><p class="noindent" ><img 
src="WebPmagPy0x.png" alt="PIC" class="graphics" width="341.43306pt" height="106.1643pt" ><!--tex4ht:graphics  
name="WebPmagPy0x.png" src="EPSfiles/tauxe12-magic.eps"  
-->
<!--l. 132--><p class="noindent" >Unpack the data using the program in &#x00A0;<a 
href="#x1-120000.2.7">0.2.7<!--tex4ht:ref: ex:download-magic --></a> <span 
class="cmbx-10x-x-109">download</span><span 
class="cmbx-10x-x-109">_magic.py</span>. This will unpack the
data into the different holes. Change directories into Location_2 (which contains the data for
Hole U1359A). Or, you can use the data in the <span 
class="cmbx-10x-x-109">ani</span><span 
class="cmbx-10x-x-109">_depthplot </span>directory of the example
data files as described in Section&#x00A0;<a 
href="#x1-50000.2">0.2<!--tex4ht:ref: ex:PmagPyEx --></a>.
                                                                              

                                                                              
<div class="verbatim" id="verbatim-1">
%&#x00A0;ani_depthplot.py
</div>
<!--l. 136--><p class="nopar" >
<!--l. 138--><p class="noindent" >will create the plot:
<!--l. 140--><p class="noindent" ><img 
src="WebPmagPy1x.png" alt="PIC" class="graphics" width="341.43306pt" height="286.09094pt" ><!--tex4ht:graphics  
name="WebPmagPy1x.png" src="EPSfiles/ani-depthplot.eps"  
-->
<!--l. 144--><p class="noindent" ><a name='aarm_magic.py'></a>
<!--l. 145--><p class="noindent" ><a name='subsec0-2-2'></a><h4 class="subsectionHead"><span class="titlemark">0.2.2   </span> <a 
href="#QQ2-1-7" id="x1-70000.2.2"><span 
class="cmbx-10x-x-109">aarm</span><span 
class="cmbx-10x-x-109">_magic.py</span></a></h4>
<!--l. 145--><p class="noindent" >[ <a 
href="http://webbookcopy.html#paleomagnetic_tensors" >Chapter 13</a> &amp; <a 
href="http://earthref.org/MAGIC/" >MagIC</a>]
<!--l. 151--><p class="noindent" >Anisotropy of anhysteretic or other remanence can be converted to a tensor and
used to correct natural remanence data for the effects of anisotropy remanence
acquisition. For example, directions may be deflected from the geomagnetic field direction
or intensities may be biased by strong anisotropies in the magnetic fabric of the
specimen. By imparting an anhysteretic or thermal remanence in many specific
orientations, the anisotropy of remanence acquisition can be characterized and
used for correction. We do this for anisotropy of anhysteretic remanence (aarm) by
imparting an ARM in 9, 12 or 15 positions. Each ARM must be preceded by an AF
demagnetization step. The 15 positions are given in the <a 
href="http://webbookcopy.html#15_positions" >Appendix D</a> of Tauxe
et al. (2010) For the 9 position scheme, AARMs are imparted in positions 1,2,3,
                                                                              

                                                                              
6,7,8, 11,12,13, for example. Someone (a.k.a. Peter Selkin) has kindly made the
measurements and saved them an SIO formatted measurement file named <span 
class="cmti-10x-x-109">bg.arm </span>in
the datafile directory called <span 
class="cmti-10x-x-109">aarm</span><span 
class="cmti-10x-x-109">_magic</span>. We need to first import these into the
magic_measurements format and then calculate the anisotropy tensors. These can then
be plotted or used to correct paleointensity or directional data for anisotropy of
remanence.
<!--l. 155--><p class="noindent" >So, first use the program <span 
class="cmbx-10x-x-109">sio</span><span 
class="cmbx-10x-x-109">_magic.py </span>to import the AARM data into the MagIC format.
The DC field was 50 <span 
class="cmmi-10x-x-109">&#x03BC;</span>T, the peak AC field was 180 mT, the location was &#8216;Bushveld&#8217; and the
lab protocol was AF and Anisotropy. The naming convention used Option # 3 (see help
menu).
<!--l. 157--><p class="noindent" >Then use the program <span 
class="cmbx-10x-x-109">aarm</span><span 
class="cmbx-10x-x-109">_magic.py </span>to calculate the best-fit tensor and write out the
MagIC tables: <span 
class="cmti-10x-x-109">rmag</span><span 
class="cmti-10x-x-109">_anisotropy </span>and <span 
class="cmti-10x-x-109">rmag</span><span 
class="cmti-10x-x-109">_results</span>. These files can be used to correct
remanence data in a <span 
class="cmti-10x-x-109">pmag</span><span 
class="cmti-10x-x-109">_specimens </span>format table (e.g, intensity data) for the effects of
remanent anisotropy (e.g., using the program <span 
class="cmbx-10x-x-109">thellier</span><span 
class="cmbx-10x-x-109">_magic</span><span 
class="cmbx-10x-x-109">_redo.py</span>.)
<!--l. 159--><p class="noindent" >Here is a transcript of a session that works. Note that the <span 
class="cmbx-10x-x-109">sio</span><span 
class="cmbx-10x-x-109">_magic.py </span>command is all on
one line.
                                                                              

                                                                              
<div class="verbatim" id="verbatim-2">
%&#x00A0;sio_magic.py&#x00A0;-f&#x00A0;bg.arm&#x00A0;-loc&#x00A0;Bushveld&#x00A0;-LP&#x00A0;AF:ANI&#x00A0;-F&#x00A0;aarm_measurements.txt
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;&#x00A0;&#x00A0;&#x00A0;-ncn&#x00A0;3&#x00A0;-ac&#x00A0;180&#x00A0;-dc&#x00A0;50&#x00A0;-1&#x00A0;-1
&#x00A0;<br />
&#x00A0;<br />results&#x00A0;put&#x00A0;in&#x00A0;&#x00A0;aarm_measurements.txt
&#x00A0;<br />
&#x00A0;<br />
&#x00A0;<br />%&#x00A0;aarm_magic.py
&#x00A0;<br />Processing:&#x00A0;&#x00A0;bg2.01&#x00A0;&#x00A0;Number&#x00A0;of&#x00A0;positions:&#x00A0;&#x00A0;9
&#x00A0;<br />Processing:&#x00A0;&#x00A0;bg2.03&#x00A0;&#x00A0;Number&#x00A0;of&#x00A0;positions:&#x00A0;&#x00A0;9
&#x00A0;<br />Processing:&#x00A0;&#x00A0;bg2.06&#x00A0;&#x00A0;Number&#x00A0;of&#x00A0;positions:&#x00A0;&#x00A0;9
&#x00A0;<br />......
&#x00A0;<br />specimen&#x00A0;tensor&#x00A0;elements&#x00A0;stored&#x00A0;in&#x00A0;&#x00A0;./arm_anisotropy.txt
&#x00A0;<br />specimen&#x00A0;statistics&#x00A0;and&#x00A0;eigenparameters&#x00A0;stored&#x00A0;in&#x00A0;&#x00A0;./aarm_results.txt
&#x00A0;<br />
</div>
<!--l. 176--><p class="nopar" > <a name='agm_magic.py'></a>
<!--l. 178--><p class="noindent" ><a name='subsec0-2-3'></a><h4 class="subsectionHead"><span class="titlemark">0.2.3   </span> <a 
href="#QQ2-1-8" id="x1-80000.2.3"><span 
class="cmbx-10x-x-109">agm</span><span 
class="cmbx-10x-x-109">_magic.py</span></a></h4>
<!--l. 178--><p class="noindent" >[<a 
href="http://webbookcopy.html#magnetic_hysteresis" >Chapter 5</a> &amp; MagIC: see Appendix&#x00A0;<span 
class="cmbx-10x-x-109">??</span>]
<!--l. 181--><p class="noindent" >This program imports Micromag hysteresis files into magic_measurements formatted files.
Because this program imports data into the MagIC database, specimens need also to have
sample/site/location information which can be provided on the command line. If this
information is not available, for example if this is a synthetic specimen, specify -syn for
synthetic on the command line.
<!--l. 184--><p class="noindent" >Someone named Lima Tango has measured a synthetic specimen named <span 
class="cmti-10x-x-109">myspec </span>for hysteresis
and saved the data in a file named <span 
class="cmti-10x-x-109">agm</span><span 
class="cmti-10x-x-109">_example.dat</span>. Use the program <span 
class="cmbx-10x-x-109">agm</span><span 
class="cmbx-10x-x-109">_magic.py </span>to
import the data into a magic_measurements formatted output file. These were measured
using cgs units, so be sure to set the units switch properly. [These can be plotted using
<span 
class="cmbx-10x-x-109">hysteresis</span><span 
class="cmbx-10x-x-109">_magic.py </span>or <span 
class="cmbx-10x-x-109">quick</span><span 
class="cmbx-10x-x-109">_hyst.py</span>.] You can also import IRM acquisition and DC
demagnetization curves using <span 
class="cmbx-10x-x-109">irm</span><span 
class="cmbx-10x-x-109">_magic.py</span>. <span 
class="cmbx-10x-x-109">hysteresis</span><span 
class="cmbx-10x-x-109">_magic.py </span>will calculate
various hysteresis parameters and put them in the relevant magic tables for you.
]
                                                                              

                                                                              
<div class="verbatim" id="verbatim-3">
%&#x00A0;agm_magic.py&#x00A0;-syn&#x00A0;myspec&#x00A0;-f&#x00A0;agm_example.dat&#x00A0;-u&#x00A0;cgs&#x00A0;-usr&#x00A0;"Lima&#x00A0;Tango"
&#x00A0;<br />
&#x00A0;<br />results&#x00A0;put&#x00A0;in&#x00A0;&#x00A0;./agm_measurements.txt
&#x00A0;<br />
</div>
<!--l. 191--><p class="nopar" >
<!--l. 193--><p class="noindent" ><span 
class="cmbx-10x-x-109">agm</span><span 
class="cmbx-10x-x-109">_magic.py </span>saved the data in a file called <span 
class="cmti-10x-x-109">agm</span><span 
class="cmti-10x-x-109">_measurments.txt </span>which can be combined
with other magic_measurements formatted files using <span 
class="cmbx-10x-x-109">combine</span><span 
class="cmbx-10x-x-109">_magic.py</span>. See also how to
import irm and backfield data in the help message.
<!--l. 197--><p class="noindent" >
<!--l. 197--><p class="noindent" ><a name='subsec0-2-4'></a><h4 class="subsectionHead"><span class="titlemark">0.2.4   </span> <a 
href="#QQ2-1-9" id="x1-90000.2.4"><span 
class="cmbx-10x-x-109">angle.py </span></a></h4>
<!--l. 197--><p class="noindent" >[Appendix&#x00A0;<span 
class="cmbx-10x-x-109">??</span>]
<!--l. 200--><p class="noindent" >Use the program <span 
class="cmbx-10x-x-109">angle </span>to calculate the angle (<span 
class="cmmi-10x-x-109">&#x03B1;</span>) between two directions
<span 
class="cmmi-10x-x-109">D </span>= 350<span 
class="cmmi-10x-x-109">.</span>2<span 
class="cmmi-10x-x-109">,I </span>= 26<span 
class="cmmi-10x-x-109">.</span>8;<span 
class="cmmi-10x-x-109">D </span>= 98<span 
class="cmmi-10x-x-109">.</span>6<span 
class="cmmi-10x-x-109">,I </span>= 67<span 
class="cmmi-10x-x-109">.</span>3.
                                                                              

                                                                              
<div class="verbatim" id="verbatim-4">
%&#x00A0;angle.py&#x00A0;-i
&#x00A0;<br />Declination&#x00A0;1:&#x00A0;[cntrl-D&#x00A0;&#x00A0;to&#x00A0;quit]&#x00A0;350.2
&#x00A0;<br />Inclination&#x00A0;1:&#x00A0;26.8
&#x00A0;<br />Declination&#x00A0;2:&#x00A0;98.6
&#x00A0;<br />Inclination&#x00A0;2:&#x00A0;67.3
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;72.1
&#x00A0;<br />Declination&#x00A0;1:&#x00A0;[cntrl-D&#x00A0;&#x00A0;to&#x00A0;quit]&#x00A0;^D
&#x00A0;<br />Good&#x00A0;bye
</div>
<!--l. 211--><p class="nopar" > [NB: PC users will get a more angry sounding exit message]
<!--l. 214--><p class="noindent" >You can also use this program by reading in a filename using the &#8217;-f&#8217; option or from standard
input (with <span 
class="cmmi-10x-x-109">&#x003C;</span>). Try this out with the test file in the <span 
class="cmti-10x-x-109">angle </span>directory (<span 
class="cmti-10x-x-109">angle.dat</span>). First
examine the contents of the input file using <span 
class="cmbx-10x-x-109">head, more</span>, or <span 
class="cmbx-10x-x-109">cat</span>. The use <span 
class="cmbx-10x-x-109">angle.py </span>to
calculate the angles. You can also save your output in a file <span 
class="cmti-10x-x-109">angle.out </span>with the &#8217;-F&#8217;
option:
                                                                              

                                                                              
<div class="verbatim" id="verbatim-5">
&#x00A0;%&#x00A0;head&#x00A0;angle.dat
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;&#x00A0;11.2&#x00A0;&#x00A0;&#x00A0;&#x00A0;32.9&#x00A0; &#x00A0;&#x00A0;&#x00A0;&#x00A0;6.4&#x00A0;&#x00A0;&#x00A0;-42.9
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;11.5&#x00A0;&#x00A0;&#x00A0;&#x00A0;63.7&#x00A0; &#x00A0;&#x00A0;&#x00A0;10.5&#x00A0;&#x00A0;&#x00A0;-55.4
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;11.9&#x00A0;&#x00A0;&#x00A0;&#x00A0;31.4&#x00A0; &#x00A0;&#x00A0;358.1&#x00A0;&#x00A0;&#x00A0;-71.8
&#x00A0;<br />&#x00A0;&#x00A0;349.6&#x00A0;&#x00A0;&#x00A0;&#x00A0;36.2&#x00A0; &#x00A0;&#x00A0;356.3&#x00A0;&#x00A0;&#x00A0;-45.0
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;60.3&#x00A0;&#x00A0;&#x00A0;&#x00A0;63.5&#x00A0; &#x00A0;&#x00A0;&#x00A0;58.9&#x00A0;&#x00A0;&#x00A0;-56.6
&#x00A0;<br />&#x00A0;&#x00A0;351.8&#x00A0;&#x00A0;&#x00A0;&#x00A0;37.6&#x00A0; &#x00A0;&#x00A0;&#x00A0;55.0&#x00A0;&#x00A0;&#x00A0;-45.8
&#x00A0;<br />&#x00A0;&#x00A0;345.5&#x00A0;&#x00A0;&#x00A0;&#x00A0;53.1&#x00A0; &#x00A0;&#x00A0;&#x00A0;44.8&#x00A0;&#x00A0;&#x00A0;-26.9
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;12.2&#x00A0;&#x00A0;&#x00A0;&#x00A0;20.1&#x00A0; &#x00A0;&#x00A0;&#x00A0;13.6&#x00A0;&#x00A0;&#x00A0;-54.0
&#x00A0;<br />&#x00A0;&#x00A0;352.1&#x00A0;&#x00A0;&#x00A0;&#x00A0;37.6&#x00A0; &#x00A0;&#x00A0;&#x00A0;&#x00A0;5.1&#x00A0;&#x00A0;&#x00A0;-39.9
&#x00A0;<br />&#x00A0;&#x00A0;341.2&#x00A0;&#x00A0;&#x00A0;&#x00A0;53.8&#x00A0; &#x00A0;&#x00A0;&#x00A0;25.1&#x00A0;&#x00A0;&#x00A0;-61.1
&#x00A0;<br />
&#x00A0;<br />&#x00A0;%&#x00A0;angle.py&#x00A0;-f&#x00A0;angle.dat
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;&#x00A0;75.9
&#x00A0;<br />&#x00A0;&#x00A0;119.1
&#x00A0;<br />&#x00A0;&#x00A0;103.7
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;81.4
&#x00A0;<br />&#x00A0;&#x00A0;120.1
&#x00A0;<br />&#x00A0;&#x00A0;100.9
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;95.1
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;74.1
&#x00A0;<br />&#x00A0;&#x00A0;&#x00A0;78.4
&#x00A0;<br />&#x00A0;&#x00A0;120.1
&#x00A0;<br />......
&#x00A0;<br />.
</div>
<!--l. 242--><p class="nopar" >
<!--l. 558--><p class="noindent" >
<!--l. 558--><p class="noindent" ><a name='subsec0-2-5'></a><h4 class="subsectionHead"><span class="titlemark">0.2.5   </span> <a 
href="#QQ2-1-10" id="x1-100000.2.5"><span 
class="cmbx-10x-x-109">core</span><span 
class="cmbx-10x-x-109">_depthplot.py</span></a></h4>
<!--l. 558--><p class="noindent" >[Chapter 15]
<!--l. 561--><p class="noindent" >Use the program <span 
class="cmbx-10x-x-109">core</span><span 
class="cmbx-10x-x-109">_depthplot.py </span>to plot various measurement data versus sample
depth. The data must be in the MagIC data formats. The program will plot whole core data,
discrete sample at a bulk demagnetization step, data from vector demagnetization
experiments, and so on. There are many options, so check the help menu before you
begin.
<!--l. 563--><p class="noindent" >We can try this out on some data from DSDP Hole 522, measured by Tauxe and Hartl
(1997). These can be downloaded and unpacked (see example &#x00A0;<a 
href="#x1-120000.2.7">0.2.7<!--tex4ht:ref: ex:download-magic --></a> for details, or you can
try it out on the data files in the directory <span 
class="cmbx-10x-x-109">core</span><span 
class="cmbx-10x-x-109">_depthplot</span>. You must specify a lab-protocol
                                                                              

                                                                              
(LP) for plotting. In this example, we will plot the alternating field (AF) data after the 15
mT step. The magnetizations will be plotted on a log scale and, as this is a record of the
Oligocene, we will plot the Oligocene time scale, using the calibration of Gradstein et al.
(2004), commonly referred to as &#8220;GTS04&#8221; for the the Oligocene. We are only interested in
the data between 50 and 150 meters (the -d option sets this) and we will suppress the
declinations (-D).
                                                                              

                                                                              
<div class="verbatim" id="verbatim-6">
core_depthplot.py&#x00A0;-LP&#x00A0;AF&#x00A0;15&#x00A0;-log&#x00A0;-d&#x00A0;50&#x00A0;150&#x00A0;-ts&#x00A0;gts04&#x00A0;23&#x00A0;34&#x00A0;-D
</div>
<!--l. 567--><p class="nopar" >
<!--l. 569--><p class="noindent" >will produce the plot:
<!--l. 571--><p class="noindent" ><img 
src="WebPmagPy2x.png" alt="PIC" class="graphics" width="341.43306pt" height="284.7084pt" ><!--tex4ht:graphics  
name="WebPmagPy2x.png" src="EPSfiles/core-depthplot.eps"  
-->
<!--l. 759--><p class="noindent" >
<!--l. 759--><p class="noindent" ><a name='subsec0-2-6'></a><h4 class="subsectionHead"><span class="titlemark">0.2.6   </span> <a 
href="#QQ2-1-11" id="x1-110000.2.6"><span 
class="cmbx-10x-x-109">dir</span><span 
class="cmbx-10x-x-109">_cart.py</span></a></h4>
<!--l. 759--><p class="noindent" >[Chapter 2]
<!--l. 762--><p class="noindent" >Use the program <span 
class="cmbx-10x-x-109">dir</span><span 
class="cmbx-10x-x-109">_cart.py </span>to convert the following data from declination <span 
class="cmmi-10x-x-109">D</span>, inclination <span 
class="cmmi-10x-x-109">I</span>
and intensity <span 
class="cmmi-10x-x-109">M </span>to <span 
class="cmmi-10x-x-109">x</span><sub><span 
class="cmr-8">1</span></sub><span 
class="cmmi-10x-x-109">,x</span><sub><span 
class="cmr-8">2</span></sub><span 
class="cmmi-10x-x-109">,x</span><sub><span 
class="cmr-8">3</span></sub>.
<div class="tabular"> <table id="TBL-2" class="tabular" 
cellspacing="0" cellpadding="0"  
><colgroup id="TBL-2-1g"><col 
id="TBL-2-1"><col 
id="TBL-2-2"><col 
id="TBL-2-3"></colgroup><tr 
class="hline"><td><hr></td><td><hr></td><td><hr></td></tr><tr  
 style="vertical-align:baseline;" id="TBL-2-1-"><td  style="white-space:nowrap; text-align:center;" id="TBL-2-1-1"  
class="td11"><span 
class="cmmi-10x-x-109">D</span></td><td  style="white-space:nowrap; text-align:center;" id="TBL-2-1-2"  
class="td11"> <span 
class="cmmi-10x-x-109">I </span></td><td  style="white-space:nowrap; text-align:center;" id="TBL-2-1-3"  
class="td11"><span 
class="cmmi-10x-x-109">M </span>(<span 
class="cmmi-10x-x-109">&#x03BC;</span>Am<sup><span 
class="cmr-8">2</span></sup>)</td>
</tr><tr 
class="hline"><td><hr></td><td><hr></td><td><hr></td></tr><tr  
 style="vertical-align:baseline;" id="TBL-2-2-"><td  style="white-space:nowrap; text-align:center;" id="TBL-2-2-1"  
class="td11"> 20 </td><td  style="white-space:nowrap; text-align:center;" id="TBL-2-2-2"  
class="td11">46</td><td  style="white-space:nowrap; text-align:center;" id="TBL-2-2-3"  
class="td11">   1.3     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-2-3-"><td  style="white-space:nowrap; text-align:center;" id="TBL-2-3-1"  
class="td11">175</td><td  style="white-space:nowrap; text-align:center;" id="TBL-2-3-2"  
class="td11">-24</td><td  style="white-space:nowrap; text-align:center;" id="TBL-2-3-3"  
class="td11">   4.2     </td>
</tr><tr 
class="hline"><td><hr></td><td><hr></td><td><hr></td></tr><tr  
 style="vertical-align:baseline;" id="TBL-2-4-"><td  style="white-space:nowrap; text-align:center;" id="TBL-2-4-1"  
class="td11">   </td></tr></table></div>
<!--l. 776--><p class="noindent" >You can enter <span 
class="cmmi-10x-x-109">D,I,M </span>data into data file, then running the program by typing what is after
the prompts (%) [ the other stuff is computer responses] :
                                                                              

                                                                              
<div class="verbatim" id="verbatim-7">
%&#x00A0;cat&#x00A0;&#x003E;&#x00A0;dir_cart_example.dat
&#x00A0;<br />&#x00A0;20&#x00A0;46&#x00A0;1.3
&#x00A0;<br />175&#x00A0;-24&#x00A0;4.2
&#x00A0;<br />^D
&#x00A0;<br />%&#x00A0;dir_cart.py&#x00A0;&#x003C;dir_cart_example.dat
&#x00A0;<br />8.4859e-01&#x00A0;3.0886e-01&#x00A0;9.3514e-01
&#x00A0;<br />-3.8223e+00&#x00A0;3.3441e-01&#x00A0;-1.7083e+00
</div>
<!--l. 786--><p class="nopar" >
<!--l. 788--><p class="noindent" >Or you could use <span 
class="cmbx-10x-x-109">dir</span><span 
class="cmbx-10x-x-109">_cart.py </span>interactively as in:
                                                                              

                                                                              
<div class="verbatim" id="verbatim-8">
&#x00A0;%&#x00A0;dir_cart.py&#x00A0;-i
&#x00A0;<br />
&#x00A0;<br />Declination:&#x00A0;[cntrl-D&#x00A0;&#x00A0;to&#x00A0;quit]
&#x00A0;<br />&#x00A0;Good-bye
&#x00A0;<br />
&#x00A0;<br />%&#x00A0;dir_cart.py&#x00A0;-i
&#x00A0;<br />Declination:&#x00A0;[cntrl-D&#x00A0;&#x00A0;to&#x00A0;quit]&#x00A0;20
&#x00A0;<br />Inclination:&#x00A0;46
&#x00A0;<br />Intensity&#x00A0;[return&#x00A0;for&#x00A0;unity]:&#x00A0;1.3
&#x00A0;<br />8.4859e-01&#x00A0;3.0886e-01&#x00A0;9.3514e-01
&#x00A0;<br />Declination:&#x00A0;[cntrl-D&#x00A0;&#x00A0;to&#x00A0;quit]&#x00A0;175
&#x00A0;<br />Inclination:&#x00A0;-24
&#x00A0;<br />Intensity&#x00A0;[return&#x00A0;for&#x00A0;unity]:&#x00A0;4.2
&#x00A0;<br />-3.8223e+00&#x00A0;3.3441e-01&#x00A0;-1.7083e+00
&#x00A0;<br />Declination:&#x00A0;[cntrl-D&#x00A0;&#x00A0;to&#x00A0;quit]&#x00A0;^D
&#x00A0;<br />&#x00A0;Good-bye
</div>
<!--l. 807--><p class="nopar" >
<!--l. 834--><p class="noindent" >
<!--l. 834--><p class="noindent" ><a name='subsec0-2-7'></a><h4 class="subsectionHead"><span class="titlemark">0.2.7   </span> <a 
href="#QQ2-1-12" id="x1-120000.2.7"><span 
class="cmbx-10x-x-109">download</span><span 
class="cmbx-10x-x-109">_magic.py</span></a></h4>
<!--l. 834--><p class="noindent" >[MagIC] <a 
href="http://earthref.org/MagIC" class="url" ><span 
class="cmtt-10x-x-109">http://earthref.org/MagIC</span></a>
<!--l. 837--><p class="noindent" >This program unpacks .txt files downloaded from the MagIC database into individual
directories for each location into which the individual files for each table (e.g.,
<span 
class="cmti-10x-x-109">er</span><span 
class="cmti-10x-x-109">_locations.txt, magic</span><span 
class="cmti-10x-x-109">_measurements.txt, pmag</span><span 
class="cmti-10x-x-109">_results.txt </span>and so on) get placed. As an
example, go to the MagIC data base at <a 
href="http://earthref.org/MAGIC/" class="url" ><span 
class="cmtt-10x-x-109">http://earthref.org/MAGIC/</span></a> and click on the
PMAG PORTAL link. Follow the &#8220;Search the Reference Database&#8221; link and enter &#8220;Sbarbori&#8221;
into the Author field. This will take you to the page for the publication Sbarbori et al. (2008)
. Download the latest &#8220;Smartbook&#8221; text file and save it to your desktop. Make a folder into
which you should put the downloaded txt file. Now use the program <span 
class="cmbx-10x-x-109">download</span><span 
class="cmbx-10x-x-109">_magic.py</span>
to unpack the .txt file (<span 
class="cmti-10x-x-109">zmab0099659tmp01.txt</span>).
                                                                              

                                                                              
<div class="verbatim" id="verbatim-9">
%&#x00A0;download_magic.py&#x00A0;-f&#x00A0;zmab0099659tmp01.txt
&#x00A0;<br />working&#x00A0;on:&#x00A0;&#x00A0;er_locations
&#x00A0;<br />er_locations&#x00A0;&#x00A0;data&#x00A0;put&#x00A0;in&#x00A0;&#x00A0;./er_locations.txt
&#x00A0;<br />working&#x00A0;on:&#x00A0;&#x00A0;er_sites
&#x00A0;<br />er_sites&#x00A0;&#x00A0;data&#x00A0;put&#x00A0;in&#x00A0;&#x00A0;./er_sites.txt
&#x00A0;<br />....
</div>
<!--l. 848--><p class="nopar" >
<!--l. 850--><p class="noindent" >You can examine the data using the <span 
class="cmbx-10x-x-109">PmagPy </span>programs (e.g., <span 
class="cmbx-10x-x-109">zeq</span><span 
class="cmbx-10x-x-109">_magic.py</span>).
 
</body></html> 

                                                                              


