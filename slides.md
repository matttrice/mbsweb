---
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## MBS Lesson 1
drawings:
  persist: true
transition: slide-down
css: unocss
title: Physical & Spiritual
layout: physical-spiritual
---

::left::

Genesis 1:1

<div v-click='2' class='text-xs group/ii'>
  “In the beginning God created the 
  <span class='group/ii'>HEAVENS</span> and the <span>EARTH</span>...”</div>
  <div v-click='3' class='sidebox'>
    <game-icons:archive-research class="text-2xl -mb-2" /> 
      Internal Interpretation
    </div>
  <div v-click='14' class='m-t-5'>
    Romans 1:20 <br/>
  <span 
    v-click='15' 
    class='italic font-light block leading-snug text-base'>
      If you can't see it, how can you trust it exists?
    </span>
  </div>
<div v-click='27' class='sidebox m-l-33'>Forms of what?</div>
<arrow v-click='27' v-if='$slidev.nav.clicks >= 27'
  z='2' x1='230' y1='290' x2='310' y2='322' 
  color='black' 
  width='3' 
  arrowSize='3' />

::spiritual::

<div v-click='4'>
  Heavens
</div>
<div v-click='6'>
  Invisible
</div>
<div v-click='10'>
  Unseen
</div>
<div v-click='11'>
  Eternal
</div>

<div v-click='17' class='brick'>
    <div v-click='23'> Causes</div>
</div>
<div v-click='22' class='relative m-t-9 z-2 font-normal' pos='relative' z='2'>
  Gravity Force
</div>
<div v-click='20' font='normal' pos='relative' z='2'>
  Wind Force
</div>
<div v-click='18' font='normal' m='t-1' pos='relative' z='2'>
  Electricity Force
</div>
<div v-click='28' bg="white" m='b-15' p='b-28 t-1' pos='absolute' w='full' z='1'>
    Energy
</div>

::physical::

<div v-click='4'>
  Earth
</div>
<div v-click='6'>
  Visible
</div>
<div v-click='8'>
  Seen
</div>
<div v-click='9'>
  Temporal
</div>

<div v-click='17' class='brick'>
  <div v-click='24'> Effects </div>
</div>
<div v-click='21' class='relative m-t-9 z-2 font-normal'>
  Objects Fall
</div>
<div v-click='19' class='relative z-2 font-normal'>
  Trees Move
</div>
<div v-click='17' class='relative z-2 font-normal'>
  Motors Spin
</div>
<div v-click='26' class='brick'>
  Matter
</div>

::right::

<div v-click='12'>
  Hebrews 11:1 <br/>
  <span v-click='13' 
    class='italic font-light text-base align-text-top'>
    Evidence of unseen</span>
</div>
<div v-click='5'>Colossians 1:15-16</div>
<div v-click='7'>2 Corinthians 4:17</div>
<div v-click='16' 
  class='italic font-light text-base align-text-top m-t-5'>
  Is it safe to put a paperclip in a light socket? 
</div>
<div v-click='25' class='sidebox -m-l-3'><i>What</i> is effected?</div>
<arrow 
  v-click='25' v-motion-slide-left v-if='$slidev.nav.clicks >= 25' 
  class='-m-l-155' z='3' x1='630' y1='260' x2='560' y2='322' 
  color='black' 
  width='3' 
  arrowSize='3' />

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes
-->

---

## transition: fade-out

# End of Lesson

<br>
<br>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->
