---
layout: default
title: Slayer
parent: Cards
permalink: /cards/slayer
---

### The Wizards (Limited)

table.card {
  table-layout: fixed;
  width: 400px;
  word-break: break-all;
} /* Setting the table width is important! */

table.card td {
  overflow: hidden;
} /* Hide text outside the cell. */

table.card td:nth-of-type(1) {
  width: 50px;
} /* Setting the width of column 1. */

table.card td:nth-of-type(2) {
  width: 300px;
} /* Setting the width of column 2. */

table.card td:nth-of-type(3) {
  width: 50px;
} /* Setting the width of column 3.  */

<table class="card">
  <tr>
    <td>0</td><!-- Upper-left -->
    <td>Slayer</td><!-- Title -->
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Hazard Creature</td><!-- Card Classification -->
    <td></td>
  </tr>
  <tr>
    <td><img src="/assets/images/border-land.svg"><br><br><img src="/assets/images/border-hold.svg"></td><!-- Left Sidebar -->
    <td>Two attacks (of one strike each) against the<br>
      same character. Attacker chooses defending<br>
      character. The defender map tap one<br>
      character in the same company to cancel<br>
      one of these attacks.</td><!-- Card Text -->
    <td></td>
  </tr>
  <tr>
    <td>11/–</td><!-- Shield -->
    <td></td>
    <td></td><!-- Corruption -->
  </tr>
</table>
