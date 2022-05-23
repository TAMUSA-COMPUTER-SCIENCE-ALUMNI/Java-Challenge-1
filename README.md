# Java Challenge #1
Summer coding challenge for TAMUSA students

This is a Java Object Oriented Programming challenge!

## Instructions
**College Basketball**
*The men’s NCAA Division I basketball programs are divided into conferences to maximize revenue and solidify regional rivalries. The in-conference schedule typically begins around Christmas break.  The in-conference schedule leads up to conference tournaments which then lead to the men’s NCAA Division I Basketball Tournament. During in-conference play, each team plays every other team in the conference twice. Conferences which contain more than eight teams are further divided into subdivisions. The teams in the subdivisions will play every team in their subdivision twice and then every team in the other subdivision once* 

### Requirements:

#### Develop a simulation, in Java using object-oriented programming, of an entire men’s basketball conference season, from start to finish, to include a conference tournament 

* There are six conferences:
    1.	Conference One has eight teams
    2.	Conference Two has eleven teams with a sub of six and a sub of five
    3.	Conference Three has eight teams
    4.	Conference Four has sixteen teams with two subs of eight
    5.	Conference Five has twelve teams with two subs of six
    6.	Conference Six has ten teams with two subs of five

* Each team will have an ability score using the following characteristics:
    * normal distribution mean = 100
    * standard deviation = 15

* Each team will be given an ID number

* Members of Conference One will have IDs 101-108 

* Conference Two has IDs 201 to 211 Etc

* Each team will begin the season with a record of 0 and 0 (No wins, no losses)

* Match results are calculated by:
    1.	S = higher ability score, W=weaker ability score
    2.	Compute difference = S-W
    3.	Sigma = Standard deviation = difference / 3 or fifteen, whichever is greater.
    4.	Stronger team generates a number with average = S, sigma
    5.	Weaker team generates a number with average = W, sigma
 
* The conference season consists of sixteen weeks
    * Games are played on 'Tuesdays' and 'Saturdays'
        * There must be at least one game on every Tuesday and Saturday in each of the sixteen weeks
        * Game results for each Tuesday and Saturday must be displayed individually upon user input
        * Conference Standings (by division if applicable) must also be displayed upon user input
        * The final standings of conference play will determine each conference’s seeding
* Conference post-season
    * Tournaments are “seeded”
        * The goal of seeding is to separate the best teams at the beginning as much as possible
    * Teams will be seeded according to the following criteria:
        1.	Head to head results
        2.	If the head to head is circular, that is A beat B, B beat C, and C beat A then 
            a.	Winning percentage will be used
            b.	If winning percentage is tied then teams are randomly placed
    * Before each conference tournament:
        * The seeding must be displayed before tournament play, based on user input
    * Conference tournament results (from first to last place):
        * Each must be displayed on user input.
* National championship tourament
    * Conference tournament winners and the two top non-winners by highest total winning percentage including tournament play will be seeded: 
        * Seeding for the National Tournament is based on the conference champion’s total winning percentage including tournament play.
        * The two non-champions will be seated #7 and #8 with the better total winning percentage being #7.
        * The seeding must be displayed before tournament play based on user input.
    * Final tournament champions will get a full screen display
    * Display will include their school name and “2022 NCAA Division I Men’s Basketball National Champions”
    * The tournament results (from first to last place) can then be displayed on user input

#### Final product

* Project must be posted to a public GitHub repository
    * The repository should contain two branches:
        1. main 
            * should match contents in dev
            * should have a limited number of commits (best, 1 per sprint)
        2. dev
    * A stand alone .jar that allows the program to be run
        * must be posted as a release under your main respository



## License
MIT License

Copyright (c) 2022 TAMUSA Computer Science Alumni Association

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
