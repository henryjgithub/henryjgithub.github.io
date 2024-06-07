---
layout: post
title: "HERITABILITY"
katex: true
---
Work:
- Understand what heritability is, variance divided by variance?
	- What does it mean when one value goes up and one goes down?
	- What does a heritability of p=1 mean vs p=0?

<hr>

Defined: Phenotype Variance:
\$$ V_{P} = V_{G} + V_{E}\$$
- Where \$V_{P}\$ is the variance of a phenotype. \$V_{G}\$ and \$V_{E}\$ is the variance of the genetic component of a phenotype and the environment component, respectively.

Defined: Broad-Sense Heritability:
\$$ h_{B} = \frac{V_{G}}{V_P} = \frac{V_{G}}{V_{G}+V_{E}} \$$

Defined: Narrow-Sense Heritability:
\$$ h_{N} = \frac{V_{G,A}}{V_P} = \frac{V_{G,A}}{V_{G,A}+V_{G,D}+V_{E}} \$$
- Additive Genetic Variance, \$V_{G,A}\$: This is the variation in a trait that comes from the sum of the effects of individual genes spread across the entire genome. Imagine each gene contributing a bit to the trait, and these contributions add up.
- Dominance Genetic Variance, \$V_{G,D}\$: Here, the variation comes from the way genes at the same spot (locus) on a chromosome interact. Sometimes one gene's effect can cover up or mask another's, and sometimes genes at different locations can interact in unexpected ways, like one gene affecting the expression of another in a non-straightforward manner.

<hr>

<details class="collapse-box"><summary class="collapse-box-title"><b>Understanding Phenotypes & Genotypes</b></summary><div markdown="1"><hr>
- Genotype = Genetics
- Phenotype = Environment(Genotype), where Environment() is a function that acts on Genotype.
  - Genetics is first and then the  environment affects the trait.
  - Definition 1, "The phenotype is the consequence of the genotype on the world. In brief, a phenotypic trait is any trait that an individual is made of!"<sup id="s1"><a href="#s1">(1)</a></sup>
  - Definition 2: "... what actually happens, including all genetic or environmental causes. The phenotypic length of your foot is, thrillingly, the actual length of your foot."<sup id="s2"><a href="#s2">(2)</a></sup>
  - Example 1: You are born with two arms and then you get mauled by a bear. Now you have 1 arm. So your phenotype of the number of arms you have is 1. The environment acts on the number of arms.
  - Example 2: If you have black hair and then you dye your hair blue. Now you have a hair color phenotype of the dyed hair color, or a hair color phenotype of blue.


<hr><p class="collapse-box-p">END</p></div></details>

<details class="collapse-box"><summary class="collapse-box-title"><b>Understanding Phenotype Variance</b></summary><div markdown="1"><hr>

- We must understand what variance first. Variance is a measure of dispersion. In the world we can measure and categorize things. 
  - If you only have brown and blue eyes than the variance is minimal because the different can only be brown or blue. If we can now dye our eye colors or where contact lenses when we measure the eye colors of people it could be anything on the spectrum. This would increase the variance.
  - Think of high variance as a shotgun and low variance as a sniper. When we shoot a shotgun the pellets go everywhere the "dispersion" is high. When we shoot a sniper the disperion is almost 0.
- So when we talk about phenotype variance we are talking about how much "dispersion" a trait has.
- In this case phenotype variance is made up of two components, genetic and environment. Further we can sub-divide phenotype variance depending on genetics into genetic additive variance and genetic dominance variance.
  - "The additive genetic variance is the genetic variance that is due to additive interaction between alleles. The dominance of genetic variance is due to non-additive interactions between allele."<sup id="s1"><a href="#s1">(1)</a></sup>

<hr><p class="collapse-box-p">END</p></div></details>

<details class="collapse-box"><summary class="collapse-box-title"><b>Understanding Broad-Sense Heritability</b></summary><div markdown="1"><hr>

- We are given the equation for heritability which is:
\$$ h_{B} = \frac{V_{G}}{V_P} = \frac{V_{G}}{V_{G}+V_{E}} \$$
- We must understand that the denominator \$V_{P}\$  is the total. Remember that \$ V_{P} = V_{G} + V_{E}\$, so when we divide \$V_{G}\$ by \$V_{P}\$ we are getting a number between [0,1].
- In this case their are two variables that vary \$V_{G}\$ and \$V_{E}\$. Let us look at a table:

<table style="background:transparent;">
	<tr>
    	<th>Case</th>
    	<th markdown="1">\$V_{G}\$</th>
    	<th markdown="1">\$V_{E}\$ </th>
    	<th markdown="1">\$ V_{P} = V_{G} + V_{E}\$ </th>
    	<th markdown="1">\$ h_{B} = \frac{V_{G}}{V_{G} + V_{E}} \$</th>
  	</tr>
  	<tr>
    	<td>1</td>
    	<td>0</td>
    	<td>0</td>
    	<td>0</td>
    	<td>undefined</td>
  	</tr>
  	<tr>
    	<td>2</td>
    	<td>0</td>
    	<td>1</td>
    	<td>1</td>
    	<td>0%</td>
  	</tr>
  	<tr>
    	<td>3</td>
    	<td>0</td>
    	<td>0</td>
    	<td>1</td>
    	<td>100%</td>
  	</tr>
  	<tr>
    	<td>4</td>
    	<td>0</td>
    	<td>1</td>
    	<td>2</td>
    	<td>50%</td>
  	</tr>
</table> 

- Remember this is variance, variance can be any positive real number, it does not need to be in the range of [0,1]. The table above is just an example.
- [Case 2] talks about a situation in which there is no genetic variation. The phenotype is expressed all in the environment. A case where genetic variation will be 0 is if in the sample of humans we get that genotype is the same.
  - For example if all humans were exactly 6ft. The variance would be 0, since there is no dispersion(think of shotgun vs. sniper example).
  - Another example is that we all have two arms.
  - This means that the only phenotypic variation is in environment. Like if you got mauled by a bear and you lost one arm.
- In [Case 3], it is the opposite of [Case 2]. We have no environmental variance. An example of this would be if every baby(in this case they differ genetically) is given the same environment. Meaning they get the same meals they get the same nutrition, exercise, they do everything the same (very scary I know). All of their phenotype differences are then influenced by their genetics. So let us say we had control like we said above. And then we measured their heights. The difference then must be their genetics. Since we controlled for environment perfectly.
- In [Case 4], there is a balance of genetic variance and environmental variance. We say that 50% of variation is due to genetics. So if we chose weight as the phenotype 50% of the variation is due to genetics and the other 50% is due to environment.
- Note in [Case 1], everyone must be a clone (no genetic variation) and everyone must be controlled environmentally.


<hr><p class="collapse-box-p">END</p></div></details>


<hr>

<sup id="s1"><a href="#s1">(1)</a></sup>
[Why is a heritability coefficient not an index of how "genetic" something is?](https://biology.stackexchange.com/questions/42273/why-is-a-heritability-coefficient-not-an-index-of-how-genetic-something-is)

<sup id="s2"><a href="#s2">(2)</a></sup>
[It’s perfectly valid for a trait to be more than 100% heritable](https://dynomight.net/heritability/)

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
