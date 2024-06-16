Hello, I am a (bad) university student from France that has studied biology for four years, now hoping to go to computer science, and eventually come back to biology through bioinformatics.

My first experience with programming was in middle school with [Scratch](https://scratch.mit.edu/). It felt more like playing more than anything else. I would always be first to finish whatever task was given, so much so, that I was signed up for some kind of national programming contest. I believe it was organized by [Castor Informatique France](https://concours.castor-informatique.fr/). However, I failed one of the test, which I still remember to this day.

One day, while on the bus, I looked through the App Store on my phone to see if there was stuff about coding, and downloaded [Sololearn](https://www.sololearn.com). I would use the app in the bus while going to school. I learned HTML, which I was thought was impressive (it's not, just use a cheatsheet), then switched to [Python](https://www.python.org/), in which I made a script that printed out the numbers of the Fibonacci sequence up to a certain value. I believe I used the app for a month or two before stopping: it has a journaling feature where you get experience every day you use the app to make you use it more. Ironically, it made me turn myself away because I missed a day.
I tried to go back to it a year or two later, but uninstalled because it had ads.

After my first year of university, I had failed my second semester, but not my first, so I had eight months of free times. During August 2021, I don't remember exactly how, but I landed on [Recueil d'exercices pour apprendre Python au lycée](https://www.codingame.com/playgrounds/17176/recueil-dexercices-pour-apprendre-python-au-lycee), I did about a hundred exercices before stopping, frustrated by the lack of explanations in later exercices.
While searching for tutorials, I found [sentdex](https://www.youtube.com/@sentdex) and his [site](https://pythonprogramming.net/), I followed his tutorials to learn Python, and it went alright. I remember my joy when tic-tac-toe worked.

Following that, I did a bunch of different things that I learned through the internet:
- Inspired by my piano professor who acquired through experience the skill to guess a note just by hearing it, I made a Python script that would play a note, and I would have to guess which one it is.
- I made a script that could run Q&As on the terminal.
- I learned enough [Blender](https://www.blender.org/) just to make a gift for my sister.
- I reworked the Q&A project as a GUI with Tkinter.
- Inspired by [Sebastian Lague](https://www.youtube.com/@SebastianLague)'s [Slime mold simulation](https://www.youtube.com/watch?v=X-iSQQgOd1A), I replicated it using [OpenCV](https://opencv.org/) with Python, then [Cython](https://cython.org/), and eventually learning C/C++ because I wasn't satisfied with the speed.
- I learned enough [OpenGL](https://opengl.org/) by following [the most famous tutorial](https://learnopengl.com/Getting-started/OpenGL) .
- I downloaded [Debian](https://debian.org/) with [WSL](https://learn.microsoft.com/en-us/windows/wsl/about), and learned a bit about Linux, I compiled some existing projects with it.
- For a relative's gift, I made a simulation in OpenGL of different chaotic attractors using [ImGui](https://github.com/ocornut/imgui) as a GUI.
- I went back to the slime mold simulation using OpenGL, it wasn't faster compared to OpenCV, so I learned how to use compute shaders.
- Looking for a way to make my code accessible to OSX, I leaned into Web: I learned of the existence of [WebGL](https://www.khronos.org/webgl/), I tried to make Conway's Game of Life, but didn't understand javascript enough to do so. I did manage to do it in regular OpenGL though.
- Next, I tried with C using [Wasm](https://webassembly.org/), but that was a bust.
- I did multiple different things during the first six months of 2023:
	- I switched to only using CMake instead of Visual Studio
	- I continued some more attempts at cellular automata, without much success.
	- I messed around with [Alda](https://alda.io/) and [Lilypond](http://lilypond.org/), music coding languages, though not a lot.
	- I messed around more with C, first with OpenGL, by making a program that would give you different parts of the [Julia set](https://en.wikipedia.org/wiki/Julia_set) depending on your cursor's position, a project that was inspired by [this video](https://www.youtube.com/watch?v=uc2yok_pLV4).
	- More with C, I learned a bit about the Win32 API, following a [tutorial](http://www.winprog.org/tutorial/). I learned the basics of the basics, but not enough to really make something with it, maybe one day I'll make an [OpenGL Context](https://www.khronos.org/opengl/wiki/Creating_an_OpenGL_Context_(WGL)).
- I finally made Conway's Game of Life with javascript using WebGL. It works on mobile as well as different computers.
- My sister gave me her old Mac, I just messed around with it and recompiled project that I had already done, the first ones being the Julia set and the chaotic attractors. I also made a version of the latter with a stereoscopic view. Unfortunately, OSX doesn't support OpenGL beyond 4.1, so there's no compute shader support.
- I tried to implement Langton's ant, but couldn't manage it for some reason using C/C++. I eventually did it using Python, with good results.
- I got interested in [Fortran](https://fortran-lang.org/), but I couldn't think of anything that I couldn't do in C. So since I knew that both are compiled languages that get turned into machine code, why not play around with Fortran C interop? And that's what I did, using Fortran in C and C in Fortran. Eventually, to really test it out, I took the OpenGL slime mold simulation project with no compute shaders, and replaced the function that changed the agents' state with a Fortran one.
- My current (very slowgoing) project is making a font using [TUNIC](https://tunicgame.com/)'s script with [Inkscape](https://inkscape.org/) and [FontForge](https://fontforge.org/). It is slow going because the glyphs of the script correspond to phonemes instead of letters.
