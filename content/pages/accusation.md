---
title: Accusation Form
date: Last Modified
permalink: /accusation/index.html
eleventyNavigation:
  key: Accusation
  order: 11
  title: Accusation Form
---

<style type="text/css">
  /* modified from https://www.sanwebe.com/2014/08/css-html-forms-designs */
  .form-style-2 label{
    display: block;
    margin: 0px 0px 15px 0px;
  }
  .form-style-2 label > span{
    width: 150px;
    font-weight: bold;
    float: left;
    padding-top: 8px;
    padding-right: 5px;
  }
  .form-style-2 input.input-field,
  .form-style-2 .textarea-field,
  .form-style-2 .select-field{
    box-sizing: border-box;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    border: 1px solid #C2C2C2;
    box-shadow: 1px 1px 4px #EBEBEB;
    -moz-box-shadow: 1px 1px 4px #EBEBEB;
    -webkit-box-shadow: 1px 1px 4px #EBEBEB;
    border-radius: 3px;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    padding: 7px;
    outline: none;
  }
  .form-style-2 .input-field:focus,
  .form-style-2 .tel-number-field:focus,
  .form-style-2 .textarea-field:focus,
  .form-style-2 .select-field:focus{
    border: 1px solid #0C0;
  }
</style>

<p>Use this form to submit your guess at the solution to the murder mystery.</p>
<p>After all forms are submitted, the confession round will ensue. The party host will read all accusations and determine the winner by who is closest to the truth.</p>
<hr>
<div class="form-style-2">
  <form name="accusation" method="POST" netlify>
    <label for="name"><span>Your Name:</span><input type="text" name="name" /></label>
    <label><span>Whodunnit?</span><select name="who">
      <option hidden disabled selected value> -- select an option -- </option>
      <option value="Dr. Chelsea Barren">Dr. Chelsea Barren</option>
      <option value="Enrique Graves">Enrique Graves</option>
      <option value="Kathryn Lawless">Kathryn Lawless</option>
      <option value="Vicki D'Adly">Vicki D'Adly</option>
      <option value="Norman D'Adly">Norman D'Adly</option>
      <option value="Michael Nightshade">Michael Nightshade</option>
    </select></label>
    <label><span>How?</span><textarea name="how"></textarea></label>
    <label><span>Why?</span><textarea name="why"></textarea></label>
    <button type="submit" class="font-bold py-2 px-6 rounded" style="border:1px solid gray;">Send</button>
  </form>
</div>