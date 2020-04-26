# Draw-it
A distance learning tool for teachers to enhance virtual teaching during COVID-19

# How to use the code
1. Download the python file
2. Make sure to install the opencv and numpy library. If you are running the file on mac, you may also need to install the opencv-python-headless package. I would recommend installing these packages using pip.
3. Navigate to the directory containing the python file and run "python draw-it.py"

Inspiration
I was inspired to create Draw it because of the difficulties most of my teachers had faced in teaching their students virtually. One of my classmates asked a question: "could you explain how to draw and label energy diagrams?" My teacher shared his screen and opened a virtual drawing pad. Then, my teacher proceeded to draw contorted lines using the trackpad on his computer. This process not only made it hard for my teacher to explain but made it difficult for students to understand the material and the challenging concepts. This inspired me to create Draw it.

What it does
Draw it is a tool incorporating computer vision that enabled teachers to draw on their screen by moving their writing implement (pen/pencil) in the air. This allows teachers to swiftly and effortlessly create diagrams or demonstrate challenging concepts to their students during the relatively short class time.

Potential Impact
Draw it has huge potential as it could help teachers across the globe provide hand-drawn explanations to students' questions, as they would do in class. Draw it would also provide a classroom-like experience for students and teachers which is essential especially since schools in my state have been closed till the next academic year.

How I built it
I used python and the OpenCV computer vision library to build Draw it. After coding the simple interface, I used the OpenCV library to detect objects blue in color (for the project to work, the implement must be blue in color). Next, the program is able to capture and draw the motion of the blue-colored object.

Challenges I ran into
I struggled a lot with finding the best data structures to work with the OpenCV library. After a lot of trial and error, I decided to use a deque to best handle the date.

What's next for Draw it
I hope to enhance Draw its features by using a machine learning model in order to perform image recognition and detect writing implements such as pens and pencils. Furthermore, I hope to expand the codebase in order to provide more tools for teachers in order to provide an even better distance learning experience for their students during COVID-19!

