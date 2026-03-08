---
layout: base
title: Crossword
permalink: /crossword/
---

<div id="puzzle-wrapper"></div>

<script src="https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.min.js"></script>
<script src="/assets/crossword/jquery.crossword.js"></script>
<link rel="stylesheet" href="/assets/crossword/crossword.css">

<script>
  // Sample puzzle data (array format)
  var puzzleData = [
    {
      clue: "State containing childhood roots",
      answer: "missouri",
      position: 1,
      orientation: "across",
      startx: 5,
      starty: 13
    },
    {
      clue: "Habit of asking 'why?' repeatedly",
      answer: "curiosity",
      position: 2,
      orientation: "across",
      startx: 1,
      starty: 4
    },
    {
      clue: "Liquid prerequisite for many good ideas",
      answer: "coffee",
      position: 3,
      orientation: "across",
      startx: 7,
      starty: 16
    },
    {
      clue: "Quiet solo hobby",
      answer: "reading",
      position: 4,
      orientation: "across",
      startx: 7,
      starty: 11
    },
    {
      clue: "Sleeping outside intentionally",
      answer: "camping",
      position: 5,
      orientation: "down",
      startx: 5,
      starty: 11
    },
    {
      clue: "Preferred way to explore nature",
      answer: "hiking",
      position: 6,
      orientation: "across",
      startx: 3,
      starty: 6
    },
    {
      clue: "Enemy of the morning routine",
      answer: "snooze",
      position: 7,
      orientation: "down",
      startx: 8,
      starty: 13
    },
    {
      clue: "Two tiny reasons productivity occasionally drops",
      answer: "cats",
      position: 8,
      orientation: "across",
      startx: 6,
      starty: 2
    },
    {
      clue: "Places that make PTO disappear quickly",
      answer: "nationalparks",
      position: 9,
      orientation: "down",
      startx: 7,
      starty: 1
    },
    {
      clue: "Game of power, policy, and persuasion",
      answer: "politics",
      position: 10,
      orientation: "down",
      startx: 4,
      starty: 1
    }
  ]

  // Initialize the crossword
  $('#puzzle-wrapper').crossword(puzzleData);
</script>