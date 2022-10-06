# JSON Movie Collection

[![Build Status](https://travis-ci.org/jsonmc/jsonmc.svg?branch=master)](https://travis-ci.org/jsonmc/jsonmc)

A comprehensive collection of movies and actors easy to use and parse in json file format segregated by release year.

## Contributing

Every October, this repository receives a lot of attention. If you want to work on any of the issues tagged Hacktoberfest, please, say so in the issue and I'll make sure to merge the PRs of those who came first.

If you're looking for issues to contribute, check those that does not have a "dibs" label. Check the comments, if nobody requested "dibs", make sure to leave your comment so you can get your PR merged first for that issue.

Make sure to always reference your pull requests with the respective issue by adding `Fixes #100` on your commit message, PR title or PR description. A template has been provided to help you out.

### A movie has the following details


Movie attribute | Details
----------------|--------------
Release date | YYYY-MM-DD release date
Categories | Action, adventure, comedy, animation, family, fantasy, sci-fi
Director | Directors of the movie
Writers | Screenplay and story writers
Actors | Main casts of the movie
Year | Movie released year
Runtime | Runtime in mins
Storyline | Brief description of the movie


#### Example movie file

```json
{
  "name": "Jurassic Park",
  "year": 1993,
  "runtime": 127,
  "categories": [
    "adventure",
    "thriller",
    "sci-fi"
  ],
  "release-date": "1993-06-11",
  "director": "Steven Spielberg",
  "writer": [
    "Michael Crichton",
    "David Koepp"
  ],
  "actors": [
    "Sam Neill",
    "Laura Dern",
    "Jeff Goldblum"
  ],
  "storyline": "Huge advancements in scientific technology have enabled a mogul ... critical security systems are shut down and it now becomes a race for survival with dinosaurs roaming freely over the island."
}
```

#### Example Series File

```json
{
  "name": "Invencible",
  "year": 2021,
  "runtime": 127,
  "episode": 8,
  "season": 1,
  "categories": [
    "Animation",
    "Image Comics",
    "sci-fi"
  ],
  "release-date": "2021-03-25",
  "director": "Robert Kirkman",
  "writer": [
    "Robert Kirkman",
    "Cory Walker"
  ],
  "actors": [	
    "Steven Yeun",
    "Sandra Oh",
    "J.K. Simmons"
  ],
  "storyline": "Mark Grayson is a normal teenager, except for the fact that his father Nolan is Omni-man, the strongest superhero on the planet. Shortly after his seventeenth birthday, Mark begins to develop his own powers and enters his father's tutelage. As Mark uses his powers for good, he discovers that his father's legacy may not be as heroic as it seems."
}
```
## Contributing

Check [Contributing Guide](contributing.markdown) for further instructions.
