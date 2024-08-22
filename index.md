---
layout: base
title: "Mene's digital garden"
---

<style>

	html {
	  scroll-behavior: smooth;
	}

	.site-header {
	  border: 1px solid black;
	}

	a.external, a.internal {
	  padding: 4px;
	  padding-left: 6px;
	  padding-right: 6px;
	  white-space: nowrap;
	}

	  a:hover {
	    opacity: .5;
	  }

	  a.external {
	    color: #ffA500;
	    border: 1px solid #ffA500; 

	  }

	   a.internal {
	    color: #A020F0;
	    border: 1px solid #A020F0; 

	  }

	h1 {
	  font-size: 28px;
	  text-transform: uppercase;
	  margin-top: 30px;
	  margin-bottom: 30px;
	}

	hr {
		border: 1px solid black;
	}

</style>


<div class="group">
	<p><b>Garden last tended to in 21.08.2024</b></p>
	<a id="scroll-link" class="internal" href="#">Go to the latest addition 🪴</a>
</div>

# Welcome

This is my personal digital garden.

I've been thinking about the concept for a while. I heard of it by my friend Tiago, who shared <a class="external" target="_blank" href="https://x.com/Mappletons/status/1250532315459194880">this Twitter thread he once read.

It's basically about hypertext and continuity: an evolving digital place, where ideas are connected through hyperlinking. There are no concerns with being linear, chronological. Things are also never finished: text, layout, images, all is subject to change. This is no newsfeed. It's a garden!

I've created this out of impulse, in a day when I was feeling restless. I've felt a creative urge, a desire to make something that is inherently mine, but that I can also share with others.

I've been writing some journals and devoting time to street photography, but those are (at least up to now) personal endeavors. I feel the urge to put stuff out there – but not something like the journalism pieces I publish as my job, but something that is, and I'm getting repetive here, personal.

Digital gardeners often create neat and ordered lawns. They may be ever growing, organic and dynamic, but they still follow at least some degree of order – tags, labels, different pages and indexes.

I, however, decided to go on without planning too much. This garden is not a well-kempt lawn, but rather an effort at<a href='https://en.wikipedia.org/wiki/Natural_landscaping' class='external' target='_blank'>natural landscaping.</a> I'm letting my uncultivated thoughts flow, with just a little bit of trimming here and there. 

My initial plan is to build a single, very long web page that you can navigate by clicking internal links. Once you click, you'll be immediately taken to some other part of the page. The eventual external links will be in orange and always open in a new tab. Internal links, that just take you to another part of the garden, will be purple instead.

That's as much thought as I'm willing to give this before starting. I'll just start writing and linking and see where this leads me. No copy-editing, no over-thinking, no design concerns. Maybe it will die in a couple days. Maybe it will linger. We'll see. 

Let's create the first hyperkink, shall we?

Please, click, and I'll take you to <a class="internal" href="#on-language">"On Language",</a> where I give my reasoning for writing in English and not in my native Portuguese language.

<hr>

# On Language

I'm a native Portuguese speaker, and I express myself much butter in my own language. However, I decided to write this in English because, just 15 minutes before starting the garden, I was reading my first Haruki Murakami book: <a class="external" href="https://www.goodreads.com/book/show/32853170-ou-a-a-can-o-do-vento-pinball-1973?ref=nav_sb_ss_1_9" target="_blank">"Ouça a canção do vento & Pinball 1973",</a> in the Portuguese name.

I still haven't gone far into reading. In fact, I was just reading the author's introduction, where he explained his writing process. It turns out that he decided to write the beginning of the novel at first in English, and to adapt it into Japanese later.

<b>Quick side note:</b> his sudden desire to express himself in a novel, which he explains on the preface, also reminded me of <a href="#welcome" class="internal">the sudden impulse for starting this garden.</a>

Anyway, back to his reasoning for using another language than japanese: since his English skills were much below his Japanese skills, he was forced to use only simple, direct, and concise sentences. And, in his opinion, this was not bad – it helped him find his voice, stripping his writing of pretentiousness and getting rid of an exaggerated concern for literary values.

I don't know how much truth there's to it, but it sounded wise, and I'm adopting it.

This is the opposite perspective of one I came across while reading another book, <a href="https://www.goodreads.com/book/show/6425806-o-apocalipse-dos-trabalhadores" target="_blank" class="external">"O apocalipse dos trabalhadores",</a> by the Portuguese author Valter Hugo Mãe. 

I don't remember much about the plot, but I recall that two lovers met repeatedly, but they didn't share a language both were proficient in. Suddenly, one of them realizes how the other (an immigrant) is struggling to conceive complex ideas and convey his feelings. She used to think that this migrant was stupid, but no – he was simply a prisioner of his lack of vocabulary.

This idea of looking stupid for not having access to the right words left a mark on me, and it still makes me anxious. I've been traveling a lot lately, and working remotely in at least three different langauges... And  I don't speak the language of my main employer! 

I often feel stupid because of this. Maybe, though, I'm not stupid as Hugo Mãe thought. Maybe I'm smart like Murakami was.

<script>
    // JavaScript to find the last <h1> and set a class
    const lastH1 = document.querySelector('h1:last-of-type');
    if (lastH1) {
        lastH1.classList.add('scroll-target');
    }

    // Add an event listener to scroll to the element with the class
    document.getElementById('scroll-link').addEventListener('click', function(e) {
        e.preventDefault();
        const targetElement = document.querySelector('.scroll-target');
        if (targetElement) {
            targetElement.scrollIntoView({ behavior: 'smooth' });
        }
    });
</script>
