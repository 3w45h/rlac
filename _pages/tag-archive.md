---
title: "Responses"
permalink: /responses/
layout: archive
author_profile: true
--- 

## Response 1


For this response, I returned to a set of visualizations generated in Voyant Tools using a corpus of fourteen Harry Potter fan fiction texts written by different authors. I selected these texts because they were part of my previous assignment and reflect material we explored in class. Although the corpus shares a common fictional universe, each text is independent, written by different authors, and varies in style, focus, and character usage. This makes it a useful case for testing how visualizations and LLMs handle fragmented but thematically related data.
To explore this, I gave my visualizations to Gemini with no context and prompted it to explain and interpret them. I then progressively added context and challenged its assumptions. What emerged was not just interpretation, but a clear pattern: the model consistently imposed narrative structure and meaning onto statistical visuals, even when that meaning was not actually present in the data.

Figure 1. Voyant Tools streamgraph showing relative frequencies of selected terms across multiple fan fiction texts.

When first presented with the streamgraph, Gemini correctly described its structure: relative word frequencies across documents, with terms like “Harry,” “Brenda,” and “said” tracked across the corpus. At this stage, its interpretation was mostly descriptive. However, it quickly began to move beyond what was visible. It identified “dominance,” “character presence,” and “dialogue-heavy sections,” which are reasonable but already interpretive.
The major shift occurred when I asked what the data was “talking about.” Gemini responded by constructing a narrative: it suggested that the visualization represented a storyline progression, where certain characters appear, disappear, and re-emerge across a continuous plot. This is where the problem becomes clear. The visualization does not represent a timeline—it represents separate texts. The model treated the x-axis as narrative time rather than a collection of independent documents.
This is not just a minor mistake. It shows how the form of the visualization encourages narrative thinking, even when it is structurally incorrect.

Figure 2. Voyant Tools TermsRadio visualization showing term prominence across documents.


The TermsRadio visualization intensified this issue. Gemini interpreted the peaks and shifts in word frequency as evidence of “story phases,” including a “Brenda disruption,” a “return to Harry,” and even a “climax” and “outro.” None of these exist in the data. They are entirely constructed.
This is a clear example of what can be called interpretive inflation: turning patterns into arguments. The visualization provides frequency variation, but Gemini transforms that into plot, character arcs, and thematic development. It is not reading the visualization—it is completing it with probabilistic narrative knowledge.
This aligns with a key insight: visualizations invite interpretation, but they do not constrain it. Without context, both humans and LLMs fill in the gaps.


Figure 3. Voyant Tools terms table displaying word counts and distribution trends across documents.

The Terms table appears more objective, presenting raw counts and trend lines. However, Gemini still overreaches. It identifies patterns such as “Snape as a third lead,” “modern prose style,” and “original characters dominating specific texts.” Some of these claims are plausible, but they are not directly supported by the visualization itself.
Importantly, when challenged, Gemini acknowledged which parts of its explanation were assumptions versus visible data. This moment is critical. It reveals that LLMs are capable of distinguishing inference from evidence, but only when explicitly prompted to do so.


Figure 4. Gemini interpreting the streamgraph without contextual information.
When I removed all context and asked Gemini to interpret the data again, it fully committed to a single-narrative reading. It described a “massive mid-story character introduction,” a “dialogue-heavy plot,” and a structured character hierarchy. These conclusions are coherent, but entirely wrong given the actual structure of the corpus.
This demonstrates a key point: LLMs prioritize coherence over correctness. They generate the most likely explanation, not the most accurate one.

Figure 5. Gemini generating a continuous storyline from non-continuous data.

After providing the correct context that the texts are separate fan fiction stories, the interpretation changed significantly. Gemini shifted from storytelling to comparison. It began identifying differences in writing style, character focus, and author preferences.

Figure 6. Gemini revising its interpretation after receiving contextual information.

However, even with context, the model continued to speculate. It labeled authors as “talkers” or “narrators,” assumed the presence of original characters, and inferred stylistic intentions. Context improved the direction of interpretation, but it also enabled more confident assumptions.
This reflects a broader insight from the course reading “People don’t read, but LLMs do.” The text argues that LLMs function as active readers of content, shaping how information is interpreted and understood. In this case, Gemini is not just reading the visualization—it is reconstructing meaning from it, using both visual signals and prior knowledge. This reinforces the idea that LLMs are not neutral interpreters; they are participants in meaning-making.

Do visuals speak for themselves? Clearly not.
This experiment shows that visualizations are highly dependent on context, and without it, both humans and LLMs are prone to overinterpretation. More importantly, it reveals that LLMs do not simply analyze visuals—they generate narratives from them, often with unwarranted confidence.
Context does not just clarify meaning; it shapes it. It guides interpretation, but it can also amplify assumptions. As a result, effective visual communication requires more than presenting data—it requires explicit framing, methodological transparency, and critical interpretation.
Ultimately, this process has made me more cautious. Computational tools and visualizations are powerful for identifying patterns, but patterns are not arguments. And when interpreted by LLMs, those patterns can quickly become stories that were never actually there.

