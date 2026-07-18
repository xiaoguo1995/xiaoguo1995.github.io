---
title: "[2026 July 14] Fast Fourier Transform (FFT) for Engineers in the Making"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/FFT_Engineers_in_the_making
venue: "The University of Queensland, School of Electrical Engineering and Computer Science"
date: 2026-07-14
location: "Brisbane, Australia"
paperurl: 'https://xiaoguo1995.github.io/files/UQ_ISB_Xiao Guo_FFT_for_Engineers_in_the_making_2026July14.pptx'
---
<style>body {text-align: justify}</style>

The FFT lecture slide 
(<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7484067093223473152?collapsed=1" height="567" width="504" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>)

[FFT lecture slide can be downloaded in Linkedin](https://www.linkedin.com/posts/xiaoguo-neuhkuuq_fast-fourier-transform-for-engineers-in-the-ugcPost-7484067093223473152-3X_T/?utm_source=share&utm_medium=member_desktop&rcm=ACoAABmkHn4Bsslcqliz8VhQaF5bsx3AuEntIO4)

I'm a lecturer of ELEC3100: Fundamental of EM waves and fields (aka. time-varying fields) since 2024.

This can be used as a 25-to-30 min FFT lecture, with optional usage of matrix-form of FFT with another 5-to-10 min.

You need to assume your students at least see the form of Fourier Integral before in 2nd year in Australia or 1st year in some other countries.

**Why this FFT Lecture**:
- Most students and professional engineers may just call FFT in real life 
- All boring math behind it
- I propose a way to explain to convince engineers in the making (students) to learn FFT in a light way
- everyone know how boring FFT can be, below in Textbook section and Online materials, you are welcome to learn in the hard way if you want.
- I always prefer to learn a new thing *in a light way* step by step and directly tell me why it is useful as my math is not good (compared a majority of genius in the rest of the world). 
- As I really do not care math soley, there are plenty of 1980s math and physics I have learnt yet, but didn't impact my life.

(Really, in reality, most engineering students will "fall asleep" and are not able to digest FFT complicated math in the typical way we taught them. 

Lecturers may also choose to skip assessing how FFT really work in final exam, as student evaluation survey plays the role.)

What is covered (the logic)
======
- (p.3 to p.7): *Why* we need Fourier Transform and its usage in real world which is FFT
- (p.8 - p.9): *What* is Fast Fourier Transform
- (p.10): *Why* FFT is called "Fast" Fourier Transform
- (p.11): *When* "Fast Fourier Transform" can be slow? 
- (p.11, p.12): A trick called zero padding 
- (p.13): FFT can be wrong, how to sample the signal properly as an engineer?
- (p.14 to p.16): 1D and 2D FFT applications (audio and image processing)
- (p.17 - p.19): FFTshift we encountered in 1D and 2D FFTapplications when we really code it up
- (p.22 - p.29): *How* does the FFT algorithm work (with a 2-point and 4-point FFT example)? 
- [Optional] (p.32 - p.36): the *generic matrix-form* of FFT with 4-point FFT example 

Textbook / Other Univ's FFT lecture materials
=====
- [MIT: The phenomenal FFT lecture by Prof. Gilbert Strang](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/resources/lecture-26-complex-matrices-fast-fourier-transform/)
- [Standard University: FFT for 2nd year student](https://see.stanford.edu/Course/EE261/121)
- [Princeton University: FFT lecture](https://home.hvl.no/ansatte/gste/ftp/MarinLab_files/Litteratur/FFT_Princeton_Uni_lect11.pdf)
- [Princeton University: FFT for 2nd year student](https://www.princeton.edu/~cuff/ele201/kulkarni_text/frequency.pdf)
- [UC Berkely: FFT; it has a cool 2D example :)](https://people.eecs.berkeley.edu/~demmel/cs170_spr07/LectureNotes/Lecture_FFT.pdf)
- [University of Pennsylvania, FFT lecture in DSP couse](https://www.engineering.upenn.edu/~ese5310/spring2022/handouts/lec20.pdf)
- [Fast Fourier Transforms by James S. Walker](https://www.taylorfrancis.com/books/mono/10.1201/9780203756188/fast-fourier-transforms-steven-krantz-james-walker)

