# lp-three-section

A element to create three columns content with image and text/legend below that 
very common in vast majority of the landing pages.

Usage
=====
The class `title`, `highlight-[1,2,3]` and `text-highlight-[1,2,3]` are required
to compose this presentation.

```
<lp-three-section minHeight="500" bgcolor="#F9F9F9" titlecolor="#979797">
      <span class="title">
      A title to all section 
      </span>
      <div class="highlight-1">
        <!-- Above content commonly put img -->
        <img-sprite src="/images/sprite-call.png"></img-sprite>
      </div>
      <div class="highlight-2">
        <img-sprite src="/images/sprite-call.png"></img-sprite>
      </div>
      <div class="highlight-3">
        <img-sprite src="/images/sprite-call.png"></img-sprite>
      </div>
      <div class="text-highlight-1">
          <!-- label text placed below above content like images -->
          Text 1 succint 
      </div>
      <div class="text-highlight-2">
          <!-- label text placed below above content like images -->
          Text 2 succint 
      </div>
      <div class="text-highlight-3">
          <!-- label text placed below above content like images -->
          Text 3 succint 
      </div>            
</lp-three-section>
```

Outcome
=======
![](https://github.com/horacioibrahim/landingpages-elements/blob/master/lp-three-section/outcome.png)
