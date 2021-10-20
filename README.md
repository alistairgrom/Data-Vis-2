# Data-Vis-2
Second coursework of DataVis module

# Motivation

You are given a selection of three volume data sets. Two of the three are
unknown and mysterious. Your job is to explore, hypothesize, and discover what
phenomena the data sets depict through the use of volume rendering. Rather than
producing a volume renderer from scratch, you are to use an existing volume
renderer called ParaView (<http://www.paraview.org>) to help you with your
exploration. As an alternative, you may develop the volume renderer using
[three.js](https://threejs.org/). *You are not restricted to the above
software. You may use any volume rendering software but you need to clear it
with me first.* 

# Tasks

Paraview is an advanced, state-of-the-art volume rendering tool freely
available for educational and research purposes. It is based on open source
volume rendering libraries which enable interactive visualization of volumetric
data sets with high flexibility. They are implemented as a multi-platform
(Windows and Linux) C++ libraries using OpenGL and GLSL for GPU-based
rendering, licensed under the terms of the GNU General Public License. In order
to accomplish this task, you are to explore the software's features (look for
"Features") with a special focus on their various volume rendering techniques
and transfer functions. three.js is is a mature javascript library for
developing 3D rendered scenes. It can be used for volume rendering (e.g.
<https://threejs.org/examples/webgl2_materials_texture3d.html>).

The aim of this assignment is to learn to use state-of-the-art volume
visualization tools. Select a tool and, for each dataset, indentify the
characteristics of the data and ultimately unravel what they are or what you
think they are.

- Can you use volume rendering to gain an overview of the data?
- Can you discover any patterns or trends in the data?
- Does the data have any features, at a large scale or a small scale?
- What do you think the data sets are?
- What phenomena do the data sets try to capture?
- Can you support your answers with visualizations that provide evidence?

You do not necessarily need to answer these questions directly. My hope is that
in the proces of doing the assignment you will discover some of the answers to
these questions.  You will do this for 3 different tasks listed below.

Your task is to use [literate visualization](https://www.gicentre.net/litvis)
to produce **five different** visual designs which can convey some meaningful
and hopefully interesting insight about the data.  You are required to supply
five unique observations about the data (and not just repeat the same
observation over and over).  For each design, fill out a literate visualization
schema as discussed in
<https://github.com/gicentre/litvis/blob/main/documents/tutorials/introduction/intro2.md>.

Each visualization design you create should be in a separate markdown file.
Unlike the first coursework, you can just embed videos or images in the
markdown file.  Thus you will have 5 files at the end.  **You must include
images and code in the markdown files** to create your visualizations.  There
is a prepared set of files at
<https://github.com/SwanseaU-TTW/csc337_volvis_cw>. 
