This minicourse in databases and SQL is part of [Computational Statistics and Operations Research](https://www.moodle.aau.dk/course/view.php?id=28948), a course held in the spring semester of 2019 at Aalborg University for 2nd semester Operations Research master students.


## Contents

Each lecture consists of a slideshow presentation of new concepts, some live examples, and individual exercises.
You should therefore bring a laptop to each lecture; see below for programs to install beforehand.

Click through below for detailed descriptions of and material for each session.

- Lecture 01: [Introduction to databases](lectures/01-introduction)
- Lecture 02: [Aggregation and JOINs](lectures/02-aggregation)
- Lecture 03: [Databases in R](lectures/03-tidyverse)
- Lecture 04: [Management and performance](lectures/04-management)
- [Self study session](lectures/self-study)


## Evaluation

To pass the minicourse, you must hand in a satisfactory solution to the self study exercise.


## Prerequisites and preparation

Some experience with the programming language R is required.

Before the first lecture:

1. Install the following on your laptop:
    + [PostgreSQL Server](http://www.postgresql.org/download)
    + [pgAdmin 4](https://www.pgadmin.org/download)
    + [R](https://cran.r-project.org/) with packages: `tidyverse`, `RPostgreSQL`, and `nycflights13`
    + [RStudio](https://www.rstudio.com) (optional, but recommended)
1. Make sure your postgres server is running and that you can connect to it in pgAdmin
1. Bring your laptop to the lectures

For a quick guide to installing and setting up PostgreSQL Server and pgAdmin 4, see the [installation and setup guide](resources/installation).

If you have problems, please contact me at <janus@math.aau.dk>.


## Literature and resources

The following resources will be used and referenced throughout the lectures:

[D&W]
: Joshua D. Drake and John C. Worsley. *Practical PostgreSQL*.  O'Reilly Media, Inc. ISBN 978-1-56592-846-6.
Available at <http://proquest.safaribooksonline.com/9781449309770>

[Docs]
: Official PostgreSQL documentation. <https://www.postgresql.org/docs/current/index.html>

Other resources and notes:

- [Installation guide](resources/installation)
- [RMarkdown cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)
- [Data wrangling cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)
- [Introduction to dbplyr](https://dbplyr.tidyverse.org/articles/dbplyr.html)
