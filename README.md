# Transparent Collections

This project aims to provide a framework, and an example using the
framework to produce an annual report, showing the scope and
accessibility of the research materials in the University of Virginia
Libraries.  Differing from other frameworks, the aim is to do so in
a way that helps Faculty across Grounds communicate with the Libraries
about what is working and what is not working about the collection.
It follows a handful of principles:

### Connection to underlying data

Wherever possible, the form of the data used by the libraries will be
provided in a separate location from the report, but connected as
clearly as feasibly to the report.  The goal of the project is to
share the Libraries sense of its collections, not to hide them in
another system, so the report must provide its sources.

### Meaningful divisions

The framework should be divided into areas that are
meaningful to faculty, but that expose major differences in
the materials.

### Best estimates

Providing a perfect report would take much more time than providing
a pretty-good report, so the aims of this project is to do the later,
but to make clear the limitations.  For example, faculty, I think,
understand that "number of titles" is a flawed way of counting the
amount of information, but it's flawed in understandable ways.
The framework tries to make these moments of estimation clear.

## Structure

The report will consist of three components, a data set, analysis of
that data, and a series of prose reports.  The data set will contain
all the data--within reason--that would be needed to conduct the
analysis.  The prose report will draw on the contents of the analysis
to explain to a particular group of faculty, what the collection
looks like.  Each of these will have a different form.

### Data set

Will be a GitHub (or other) directory of the files used to write the
report, including approval plans, statistical reports, lists of
books, etc.  While the files will be organized sensibly, no particular
effort will be made in presentation here.

* Excel sheets for approval plans
* CSV files from Director's Station
* Data from Renee in ILL (form to be determined)
* Instructions to collect all those data sets again

### Analysis of data

The analysis will be a large CSV file that gives counts of each
combination of these attributes within several mutually exclusive
categories:

* Ownership: owner, license with backup, license with no backup,
  individual license
* Finding method: in Virgo, not in Virgo but a known database, neither
  in Virgo nor a known database
* Retrieval time: minutes, hours, days, weeks, months or more
* Subject: by LC class letters from the
  [Outline](http://www.loc.gov/catdir/cpso/lcco/)
* Era: current (six months), recent (last 20 years), last-century,
  antiquarian (older)
* Market: Anglo-American, Western Europe, Eastern Asia, Latin America,
  Music, Video, [etc. by approval plans]
* Form: electronic, physical
* Browsable: physically, virtually, neither

That is: "owner, in Virgo, minutes, Z, recent, Anglo-American,
physical, physically" would be some number of titles, some number of
dollars, etc. etc.  The total number of categories would be 4 x 3 x 5
x 21 x 3 x 6 x 2 x 3 = 136,080, so they'd need to be populated by
script.  These categories are still being revised, but aim to express
the intersections of the divisions recorded by the libraries and
meaningful for serious research.  For each set of attributes, the
report will provide:

* Number of bibliographic titles (a journal is one title as is
  a monograph)
* Number of dollars spent on ownership
* Number of dollars spent on licensing
* Number of last copies of titles
* Owned copies lost/stolen/destroyed
* Owned copies found
* Number that must be recalled (count as days?)

Some of these may be difficult to figure out, or perhaps impossible,
but I'm starting with this goal for data collection.  I'd also like to
include "Number of dollars spent to maintain availability", but
I cannot figure out how to measure that one; it seems like it would
have to be salaries divided by items?  (Maybe do this...)

### Report

For a given discipline, the hope is to add up the items from the
analysis to give numbers and dollars for the collection.  The hope is
that each discipline will be able to see how resources are allocated
and discuss priorities with each other.
