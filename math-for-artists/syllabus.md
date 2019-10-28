# Math for Artists

### ITP, Spring 2020

- Instructor: Robby Kraft
- Instructor Email: rk132@nyu.edu
- Office Hours: TBD
- Costs: TBD
- Description:

In this class students will learn math tools to boost their digital practice, fix common problems, and understand the math behind our human perception of the physical world. This course spans different branches of math including geometry, linear algebra, logarithmic thinking, and statistics as they relate to a programmer making digital art with our contemporary media ecosystem. The aim of this course isn't to become calculators, rather strengthen our intuition through historical and ethnomathematics perspectives and foster a new relationship to math. The prerequisites to this class are basic arithmetic skills and an introduction to programming. We will create applications using free and open-source software, including Python and p5.js.

# Weekly Breakdown

## 1. NUMBERS

### Lecture

Course introduction: shaping numbers, coordinate systems, emergent structures, origami, linear algebra for machine learning, augmented reality.

### History

history of counting, measurement, alternate counting systems, Hellenistic geometry, the history of proofs (Euclid), numerals and the Gupta empire, early ties to astronomy, algorithms and the Islamic golden age, “Dixit algorizmi”.

### Classwork

measure pi (or measure 2pi) to as many decimal places as possible (in different number bases) (pi could have just as easily been defined as 6.28)

> use anything on the ITP floor.

### Lecture

Wrap-up: Number bases and radix. Natural, whole, rational, irrational numbers. different infinities-sizes of sets. these are the letters they typically go by.

### Homework

create a representation of an alternative counting base

## 2. FUNCTIONS

### Lecture

Arithmetic review. mod operator. mixing multiplication with addition. associative, communicative. the two sides of an equal sign. unit conversion. error.
tools, calculators, graphing.

### Classwork

with a calculator, shrink a rectangle and preserve aspect ratio. demonstrate skill w ratios.

### Lecture

transforming numbers, variable types, inputs and outputs, the number line, the dataflow language function model (pd, max-msp), function as black-box. functions-as-code model. the importance of the UNIT interval. between 0...1

### Classwork

code the map function

- SHAPING: example: random int between (13, 128) but, anything past 50 is unrecognizably similar, we need to front-load these numbers. more up front less in the back (this is the limits of map function ability)

ADVANCED FUNCTIONS: ADVANCED NUMBER SHAPING

- discrete vs. continuous methods animated
- animation curves. relating the output of Grapher with animations.

## 3. GEOMETRY (POLYTOPES)

### Lecture

Polyhedra. Regular polytopes in n-dimensions. Platonic, Archimedean, Johnson, Catalan. face-based definition, vertex-definition. VEF relationship. duality. stellation. cross-polytopes. (bring dice). open-face polyhedra. George Hart

### Classwork

calculate positions of vertices
calculate dihedral angle between faces (to account for material-thickness in construction of solids)

### Lecture

Schläfli symbols. Symmetry, rotation groups, dihedral angle. 
construction techniques, golden ratio in icosa/dodeca. engineering. collapsible structures. Chuck Hoberman. Andrea Hawksley/Vi Hart

### Homework

fabricate a polyhedron

### Sources

- [George Hart’s references](http://www.georgehart.com/virtual-polyhedra/references.html)
- [Solids, Tom Lechner](https://www.tomlechner.com/sculptures/solids.html)

## 4. GEOMETRY (TRIGONOMETRY)

### Lecture

Establishing a coordinate frame. Euclidean space. polar coordinate system (vectors). barycentric coordinate system, cylindrical coordinates

### Classwork

code a math rose. (polar coords)

### Lecture

compass straightedge solutions. Euclid. tilings, creating tessellations. distance formula (Pythagoras)

### Classwork: intersection algorithms pt. 1

- circle-circle (use the distance formula)
- line-line (segment-segment) (this will be hard)

### Lecture: Trigonometry

every little thing about triangles. atan2(), distance formula. convex-polygon overlap collision detection. all the different centers of a triangle. sine, cosine (for the FFT)

### Classwork

trisect an angle
draw a circle using sine, cosine

### Sources

- [Journey to the Center of a Triangle, Bruce & Katharine Cornwell](https://www.youtube.com/watch?v=v_oZ9Pe0yRg)
- [Paul Bourke, Geometry](http://paulbourke.net/geometry/)

## 5. LINEAR ALGEBRA

Vectors and scalars. Line representations: (point, vector) (point, point) (vector, scalar-distance-to-center)

### Lecture: intersection algorithms pt. 2
- circle-circle (now with collision detection. a vector to express repel-direction)
- line-line (segment-segment)
- point-in-polygon, convex polygons
- poly-poly, line-poly

### Lecture: computer graphics pt. 1

coordinate system as matrices. affine transforms.

### Sources
- Measurement by Paul Lockhart, section 2 Time and Space.
- 3blue1brown essence of linear algebra, first 3 videos. (30 minutes)
- [Paul Bourke, Geometry](http://paulbourke.net/geometry/)

## 6. LINEAR ALGEBRA

### Lecture: computer graphics

matrices, screen-to-world transforms and visa-versa. manipulate space with matrices. the matrix stack, how does AR work?

- orientation, Euler angles, quaternions. distance formula and trigonometry in 3D. 3D rotation math.

### Lecture

Dot and Cross products

### Homework

create a 3D environment (WebGL) that tracks with the orientation sensors of your mobile device

### Sources

- 3blue1brown essence of linear algebra

## 7. LOGARITHMS

### Lecture

"what number is halfway between 1 and 9?", Stanislas Dehaene and how logarithmic thinking is innate and unlearned. This informs the nature of human senses, audio and visual, the mathematical relationship between musical pitches, and noise and compression.

### Classwork

Explore logarithms by folding the Fibonacci sequence and deriving the golden ratio. We convert between linear and log scales, plot the Fibonacci sequence. n^x and log() can be used to convert between linear and logarithmic.

- arithmetic vs. geometric
- arithmetic mean vs. geometric mean

Fibonacci (and other exponential) sequences, log graphs, infinite series approximations, the golden, silver ratios, logarithm in senses: audial, visual, haptic

### Homework

Construct a linear representation of a logarithmic situation (example: a map of the solar system with correct positions of the planets)

### Sources

Randall Munroe’s logarithmic maps

## 8. AUDIOVISUAL

### Lecture

- human audio hearing range. frequency and timbre, consonance and dissonance, synthesis, filters. frequency spectrogram.
- information limits. Nyquist frequency. audio bit-rate. what does low bit-rate sound like? compression in both visual and audio, quantization

### Lecture

- Fourier series, Fourier synthesis, FFT. Oscilloscopes. Linkages. Kempe’s Universality theorem

### Classwork

Linkages, Fourier drawing.

### Lecture

- color space. 3-space. (cylindrical coordinate system). additive and subtractive colors. pixels. image bit-resolution
- image compression (JPEG). discrete cosine transform.
- blur and canny edge.

## 9. ALGORITHMS

### History

Math in early 20th century: Hilbert, Russell, Gödel, and Turing.

### Lecture

Formal grammars, regular expressions, Aristid Lindenmayer and plant growth patterns, finite Automata, string-rewrite systems, L-systems.

### Classwork

- L-systems (trees, dragon curve, Towers of Hanoi)

### Lecture

algorithms. broadly speaking. introduction. types of algorithms like divide and conquer.
crystal growth. state. storage medium.

### Classwork

create a Voronoi diagram using origami

### Homework

- Voronoi

### Reading

- [Examples of L-Systems, Wikipedia](https://en.wikipedia.org/wiki/L-system#Examples_of_L-systems)

## 10. COMPUTATIONAL MATH

### Lecture

the paradigm shift of the 20th century- algorithms can easily be looped millions of times. memory storage is theoretically infinite, Turing tape.

### Classwork

elementary cellular automata

### Lecture

Kolmogorov complexity, lossless representations. order. emergence, weak and strong. state machines.

Boolean Algebra:

- boolean operations, duality, reduction. `( a` `**&& b**` `) == !( a` `**|| b**` `)`
- logic gates
- finite automata

### Classwork

it’s possible to make the same fractal (dragon, Sierpinski) using a variety of methods

- l-systems
- elementary cellular automata
- recursive draw call
- origami

### Lecture

this discussion is entirely about epsilons, floating point comparison, range of error, weird ways that math becomes corrupted when simulated on a computer.

- floating points need to be cropped
- arbitrary decisions we've had to make (row vs column order matrices)
- dividing integers

### Lecture

Algorithms at scale. Encryption. Units of algorithm time: big-o. NP Hardness. non-invertible functions. one way functions.

- classes of algorithms like divide and conquer

## 11. RANDOMNESS

### History

1970’s, algorists employing randomness especially in visual art. Aleatoric music. Fluxus
computer’s pseudo random generator, testing random number generators

- White noise, brown noise, pink noise, Brownian motion, drunk walk, seeding a random number generator

### Classwork

- simplex noise

### Sources

- The Book of Shaders- [Random](https://thebookofshaders.com/10/) + [Noise](https://thebookofshaders.com/11/)
- John D. Cook, "Testing a Random Number Generator”

----------

### Week 11 - Begin planning final projects

----------

## 12. FOLDING ALGORITHMS

### Lecture

Origami axioms and relationships to Hellenistic compass ruler geometry.

### Lecture

Crumpling paper. crease patterns. graphs and planar graphs. Kawasaki’s and Maekawa’s theorems. circle packing, uniaxial tree design. origami tessellations, tiling.

### Classwork

create a tiling origami twist. fold it.
origami package design. origami collapsible living structures.

### Homework

origami tessellation

### Source
- [Ron Resch Paper and Stick Film](https://vimeo.com/36122966)
- [Geometric Folding Algorithms, MIT OCW](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/)
- [Geometric Folding Algorithms the book](https://www.google.com/books/edition/Geometric_Folding_Algorithms/ycYLAQAAQBAJ)
- [Twists Tilings and Tessellations, Robert Lang](https://www.amazon.com/Twists-Tilings-Tessellations-Mathematical-Geometric/dp/1138563064)

## 13. STRANGE SURFACES

- knots, orientable surfaces, möbius strip, donuts. Higher dimensional regular polytopes.
- 4D projections into 3D, shadows, slicing. Flatland. translation between dimensions. Henry Segerman
- higher dimensions and machine learning.

### Sources

- Flatland
- [Henry Segerman](https://math.okstate.edu/people/segerman/)
- [Mike Tanis](https://www.instagram.com/miketanis_/)
- [Alison Martin](https://www.flickr.com/photos/109333486@N07/albums)
- [Andrea Hawksley](http://octahedralgroup.org/blog/topologically-interesting-felt/)

## 14. Final Presentations

# Tisch School of the Arts

### STATEMENT OF ACADEMIC INTEGRITY

Plagiarism is presenting someone else’s work as though it were your own. More specifically, plagiarism is to present as your own: A sequence of words quoted without quotation marks from another writer or a paraphrased passage from another writer’s work or facts, ideas or images composed by someone else.

### STATEMENT OF PRINCIPLE

The core of the educational experience at the Tisch School of the Arts is the creation of original academic and artistic work by students for the critical review of faculty members.  It is therefore of the utmost importance that students at all times provide their instructors with an accurate sense of their current abilities and knowledge in order to receive appropriate constructive criticism and advice.  Any attempt to evade that essential, transparent transaction between instructor and student through plagiarism or cheating is educationally self-defeating and a grave violation of Tisch School of the Arts community standards.  For all the details on plagiarism, please refer to page 10 of the Tisch School of the Arts, Policies and Procedures Handbook, which can be found online at: http://students.tisch.nyu.edu/page/home.html

### STATEMENT ON ACCESSIBILITY

Please feel free to make suggestions to your instructor about ways in which this class could become more accessible to you.  Academic accommodations are available for students with documented disabilities. Please contact the Moses Center for Students with Disabilities at 212 998-4980 for further information.

### STATEMENT ON COUNSELING AND WELLNESS

Your health and safety are a priority at NYU. If you experience any health or mental health issues during this course, we encourage you to utilize the support services of the 24/7 NYU Wellness Exchange 212-443-9999. Also, all students who may require an academic accommodation due to a qualified disability, physical or mental, please register with the Moses Center 212-998-4980. Please let your instructor know if you need help connecting to these resources.

### STATEMENT ON USE OF ELECTRONIC DEVICES

Laptops will be an essential part of the course and may be used in class during workshops and for taking notes in lecture. Laptops must be closed during class discussions and student presentations.  Phone use in class is strictly prohibited unless directly related to a presentation of your own work or if you are asked to do so as part of the curriculum.

### STATEMENT ON TITLE IX

Tisch School of the Arts to dedicated to providing its students with a learning environment that is rigorous, respectful, supportive and nurturing so that they can engage in the free exchange of ideas and commit themselves fully to the study of their discipline. To that end Tisch is committed to enforcing University policies prohibiting all forms of sexual misconduct as well as discrimination on the basis of sex and gender.  Detailed information regarding these policies and the resources that are available to students through the Title IX office can be found by using the following link: Title IX at NYU.