<div class="box full">

# 😥 The problem 😥

<div class="content">

We can describe sequence features in open formats (such as `.gb`), but not cloning strategies.

Let's imagine a typical strategy to clone a gene into a plasmid through Gibson assembly:

<div class="img-wrapper">
    <img width="70%" src="cloning_strategy.svg" alt="">
</div>

<span style="font-size: 2em;">🤔</span> There must be an Open Standard to represent this, since it is routinely done in **hundreds of laboratories**.

<div class="img-wrapper">
    <img width="65%" src="meme.svg" alt="">
</div>

<div class="alert alert-info text-center mx-auto mt-3" role="alert" style="display: flex; justify-content: center; align-items: center;">
<div style="font-size: 2em;margin-left: 30px">😔</div>
<div class="mx-3"> No standards means no way to automate tasks or design tools </div>
<div style="font-size: 2em;margin-right: 30px">😔</div>

</div>
</div>
</div>

<div class="box full">

# 🧙 The solution 🧙

<div class="content">

## 🤖 A data model to represent cloning strategies

Every <span class="sequence-span" >Sequence</span> comes from a <span class="source-span" >Source</span> representing:

<div style="display: flex; justify-content: center; align-items: top;">
    <div class="text-center">
        <div> a) An external import</div>
        <div class="img-wrapper">
            <img width="90%" src="source_import.png" alt="">
        </div>
    </div>
    <div class="text-center">
        <div> b) A cloning step</div>
        <div class="img-wrapper">
            <img width="90%" src="source_experiment.png" alt="">
        </div>
    </div>
</div>

<div class="mb-5"></div>

## 🤩 An amazing Open Source web application

Enter 🔥🔥 **ShareYourCloning** 🔥🔥, a web application where you can simulate your cloning strategy and export it in this format to share with others or for publication.


<div class="img-wrapper">
    <img width="70%" src="architecture2.svg" alt="">
</div>

<div class="mb-5"></div>

## 🐍 Extending and maintaining cloning libraries

As part of the project I maintain, use and extend **pydna**, a BioPython-based library to simulate cloning.

If you are into scripting and want to automate your cloning, you might want to try it.

<pre class="text-white mx-5 p-4" style="background-color: #333;">
<code>> pip install pydna</code>
</pre>


</div>







</div>
</div>

<div class="box full">

# 🙋 Try it yourself! 🙋‍♂️

<div class="content centered">

<div class="img-wrapper">
    <img width="90%" src="app_screenshot.png" alt="">
</div>

<div style="display: flex; justify-content: center; align-items: center; gap: 2em;">
<div class="img-wrapper">
    <div>Web application</div>
    <img width="170em" src="qr_app.png" alt="">
</div>

<div class="img-wrapper">
    <div>GitHub repository</div>
    <img width="170em" src="qr_repo.png" alt="">
</div>
</div>

<a href="https://shareyourcloning.org/">https://shareyourcloning.org/</a>

</div>
</div>




</div>