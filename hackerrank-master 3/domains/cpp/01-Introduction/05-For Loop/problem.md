A _for_ loop is a programming language statement which allows co/e to be repeatedly executed.

The syntax for this is

```
for ( <expression_1> ; <expression_2> ; <expression_3> )
    <statement>

```

*   _expression_1_ is used for intializing variables which are generally used for controlling terminating flag for the loop.
*   _expression_2_ is used to check for the terminating condition. If this evaluates to false, then the loop is terminated.
*   _expression_3_ is generally used to update the flags/variables.

A sample loop will be

```
for(int i = 0; i < 10; i++) {
    ...
}

```

**Input Format**

You will be given two positive integers, <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-14-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-60" style="width: 0.68em; display: inline-block;"><span style="display: inline-block; position: relative; width: 0.544em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.899em 1000em 2.622em -0.359em); top: -2.482em; left: 0.002em;"><span class="mrow" id="MathJax-Span-61"><span class="mi" id="MathJax-Span-62" style="font-family: MathJax_Math-italic;">a</span></span><span style="display: inline-block; width: 0px; height: 2.486em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 0.669em; vertical-align: -0.053em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-14">a</script> and <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-15-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-63" style="width: 0.589em; display: inline-block;"><span style="display: inline-block; position: relative; width: 0.454em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.673em 1000em 2.622em -0.359em); top: -2.482em; left: 0.002em;"><span class="mrow" id="MathJax-Span-64"><span class="mi" id="MathJax-Span-65" style="font-family: MathJax_Math-italic;">b</span></span><span style="display: inline-block; width: 0px; height: 2.486em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.003em; vertical-align: -0.053em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-15">b</script> (<span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-16-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-66" style="width: 2.848em; display: inline-block;"><span style="display: inline-block; position: relative; width: 2.306em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.899em 1000em 2.983em -0.359em); top: -2.708em; left: 0.002em;"><span class="mrow" id="MathJax-Span-67"><span class="mi" id="MathJax-Span-68" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-69" style="font-family: MathJax_Main; padding-left: 0.273em;">≤</span><span class="mi" id="MathJax-Span-70" style="font-family: MathJax_Math-italic; padding-left: 0.273em;">b</span></span><span style="display: inline-block; width: 0px; height: 2.712em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.114em; vertical-align: -0.219em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-16">a \le b</script>), separated by a newline.

**Output Format**

For each integer <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-17-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-71" style="width: 4.7em; display: inline-block;"><span style="display: inline-block; position: relative; width: 3.796em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.809em 1000em 3.119em -0.404em); top: -2.708em; left: 0.002em;"><span class="mrow" id="MathJax-Span-72"><span class="mi" id="MathJax-Span-73" style="font-family: MathJax_Math-italic;">n</span><span class="mo" id="MathJax-Span-74" style="font-family: MathJax_Main; padding-left: 0.273em;">∈</span><span class="mo" id="MathJax-Span-75" style="font-family: MathJax_Main; padding-left: 0.273em;">[</span><span class="mi" id="MathJax-Span-76" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-77" style="font-family: MathJax_Main;">,</span><span class="mi" id="MathJax-Span-78" style="font-family: MathJax_Math-italic; padding-left: 0.183em;">b</span><span class="mo" id="MathJax-Span-79" style="font-family: MathJax_Main;">]</span></span><span style="display: inline-block; width: 0px; height: 2.712em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.336em; vertical-align: -0.386em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-17">n \in [a, b]</script> (so all numbers in that range):

*   If <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-18-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-80" style="width: 5.242em; display: inline-block;"><span style="display: inline-block; position: relative; width: 4.248em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.899em 1000em 2.983em -0.314em); top: -2.708em; left: 0.002em;"><span class="mrow" id="MathJax-Span-81"><span class="mn" id="MathJax-Span-82" style="font-family: MathJax_Main;">1</span><span class="mo" id="MathJax-Span-83" style="font-family: MathJax_Main; padding-left: 0.273em;">≤</span><span class="mi" id="MathJax-Span-84" style="font-family: MathJax_Math-italic; padding-left: 0.273em;">n</span><span class="mo" id="MathJax-Span-85" style="font-family: MathJax_Main; padding-left: 0.273em;">≤</span><span class="mn" id="MathJax-Span-86" style="font-family: MathJax_Main; padding-left: 0.273em;">9</span></span><span style="display: inline-block; width: 0px; height: 2.712em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.114em; vertical-align: -0.219em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-18">1 \le n \le 9</script>, then print the English representation of it. That is "one" for 1, "two" for 2, and so on.
*   Else if <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-19-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-87" style="width: 3.028em; display: inline-block;"><span style="display: inline-block; position: relative; width: 2.441em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.899em 1000em 2.893em -0.404em); top: -2.708em; left: 0.002em;"><span class="mrow" id="MathJax-Span-88"><span class="mi" id="MathJax-Span-89" style="font-family: MathJax_Math-italic;">n</span><span class="mo" id="MathJax-Span-90" style="font-family: MathJax_Main; padding-left: 0.273em;">></span><span class="mn" id="MathJax-Span-91" style="font-family: MathJax_Main; padding-left: 0.273em;">9</span></span><span style="display: inline-block; width: 0px; height: 2.712em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.003em; vertical-align: -0.108em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-19">n > 9</script> and it is even, then print "even".
*   Else if <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-20-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-92" style="width: 3.028em; display: inline-block;"><span style="display: inline-block; position: relative; width: 2.441em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.899em 1000em 2.893em -0.404em); top: -2.708em; left: 0.002em;"><span class="mrow" id="MathJax-Span-93"><span class="mi" id="MathJax-Span-94" style="font-family: MathJax_Math-italic;">n</span><span class="mo" id="MathJax-Span-95" style="font-family: MathJax_Main; padding-left: 0.273em;">></span><span class="mn" id="MathJax-Span-96" style="font-family: MathJax_Main; padding-left: 0.273em;">9</span></span><span style="display: inline-block; width: 0px; height: 2.712em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.003em; vertical-align: -0.108em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-20">n > 9</script> and it is odd, then print "odd".

**Note:** <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-21-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-97" style="width: 2.441em; display: inline-block;"><span style="display: inline-block; position: relative; width: 1.99em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(1.809em 1000em 3.119em -0.269em); top: -2.708em; left: 0.002em;"><span class="mrow" id="MathJax-Span-98"><span class="mo" id="MathJax-Span-99" style="font-family: MathJax_Main;">[</span><span class="mi" id="MathJax-Span-100" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-101" style="font-family: MathJax_Main;">,</span><span class="mi" id="MathJax-Span-102" style="font-family: MathJax_Math-italic; padding-left: 0.183em;">b</span><span class="mo" id="MathJax-Span-103" style="font-family: MathJax_Main;">]</span></span><span style="display: inline-block; width: 0px; height: 2.712em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.336em; vertical-align: -0.386em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-21">[a, b]</script> represents the interval, i.e., <span class="MathJax_Preview"></span><span class="MathJax" id="MathJax-Element-22-Frame" role="textbox" aria-readonly="true"><nobr><span class="math" id="MathJax-Span-104" style="width: 25.025em; display: inline-block;"><span style="display: inline-block; position: relative; width: 20.327em; height: 0px; font-size: 123%;"><span style="position: absolute; clip: rect(2.08em 1000em 3.39em -0.269em); top: -2.979em; left: 0.002em;"><span class="mrow" id="MathJax-Span-105"><span class="mo" id="MathJax-Span-106" style="font-family: MathJax_Main;">[</span><span class="mi" id="MathJax-Span-107" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-108" style="font-family: MathJax_Main;">,</span><span class="mi" id="MathJax-Span-109" style="font-family: MathJax_Math-italic; padding-left: 0.183em;">b</span><span class="mo" id="MathJax-Span-110" style="font-family: MathJax_Main;">]</span><span class="mo" id="MathJax-Span-111" style="font-family: MathJax_Main; padding-left: 0.273em;">=</span><span class="mo" id="MathJax-Span-112" style="font-family: MathJax_Main; padding-left: 0.273em;">{</span><span class="mi" id="MathJax-Span-113" style="font-family: MathJax_Math-italic;">x</span><span class="mo" id="MathJax-Span-114" style="font-family: MathJax_Main; padding-left: 0.273em;">∈</span><span class="texatom" id="MathJax-Span-115" style="padding-left: 0.273em;"><span class="mrow" id="MathJax-Span-116"><span class="mi" id="MathJax-Span-117" style="font-family: MathJax_AMS;">Z</span></span></span><span class="mspace" id="MathJax-Span-118" style="height: 0.002em; vertical-align: 0.002em; width: 0.183em; display: inline-block; overflow: hidden;"></span><span class="texatom" id="MathJax-Span-119"><span class="mrow" id="MathJax-Span-120"><span class="mo" id="MathJax-Span-121" style="font-family: MathJax_Main;">|</span></span></span><span class="mspace" id="MathJax-Span-122" style="height: 0.002em; vertical-align: 0.002em; width: 0.183em; display: inline-block; overflow: hidden;"></span><span class="mtext" id="MathJax-Span-123" style="font-family: MathJax_Main;"> </span><span class="mi" id="MathJax-Span-124" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-125" style="font-family: MathJax_Main; padding-left: 0.273em;">≤</span><span class="mi" id="MathJax-Span-126" style="font-family: MathJax_Math-italic; padding-left: 0.273em;">x</span><span class="mo" id="MathJax-Span-127" style="font-family: MathJax_Main; padding-left: 0.273em;">≤</span><span class="mi" id="MathJax-Span-128" style="font-family: MathJax_Math-italic; padding-left: 0.273em;">b</span><span class="mo" id="MathJax-Span-129" style="font-family: MathJax_Main;">}</span><span class="mo" id="MathJax-Span-130" style="font-family: MathJax_Main; padding-left: 0.273em;">=</span><span class="mo" id="MathJax-Span-131" style="font-family: MathJax_Main; padding-left: 0.273em;">{</span><span class="mi" id="MathJax-Span-132" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-133" style="font-family: MathJax_Main;">,</span><span class="mtext" id="MathJax-Span-134" style="font-family: MathJax_Main; padding-left: 0.183em;"> </span><span class="mi" id="MathJax-Span-135" style="font-family: MathJax_Math-italic;">a</span><span class="mo" id="MathJax-Span-136" style="font-family: MathJax_Main; padding-left: 0.228em;">+</span><span class="mn" id="MathJax-Span-137" style="font-family: MathJax_Main; padding-left: 0.228em;">1</span><span class="mo" id="MathJax-Span-138" style="font-family: MathJax_Main;">,</span><span class="mo" id="MathJax-Span-139" style="font-family: MathJax_Main; padding-left: 0.183em;">…</span><span class="mo" id="MathJax-Span-140" style="font-family: MathJax_Main; padding-left: 0.183em;">,</span><span class="mi" id="MathJax-Span-141" style="font-family: MathJax_Math-italic; padding-left: 0.183em;">b</span><span class="mo" id="MathJax-Span-142" style="font-family: MathJax_Main;">}</span></span><span style="display: inline-block; width: 0px; height: 2.983em;"></span></span></span><span style="border-left-width: 0.003em; border-left-style: solid; display: inline-block; overflow: hidden; width: 0px; height: 1.336em; vertical-align: -0.386em;"></span></span></nobr></span><script type="math/tex" id="MathJax-Element-22">[a, b] = \{x \in \mathbb{Z} \,|\, ~a \le x \le b\} = \{a, ~a+1, \dots, b\}</script>

**Sample Input**

```
8
11

```

**Sample Output**

```
eight
nine
even
odd

```