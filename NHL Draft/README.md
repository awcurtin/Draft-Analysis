<p>Notes that I couldn't fit on the slides:</p>
<p>1. Some (very few) players have negative Career Point Shares. I've zeroed these outcomes out, because drafting a horrible NHL player is probably at least as good as not drafting an NHL player at all.</p>
<p>2. When you play around with draft efficiency after pick x, you'll see that a lot of the draft efficiency percentages go to 0 if teams can't find value in later rounds. At that point, there's not much value in ranking them, although my general rule is to order them based on Perfect Draft Value. The team with the most opportunities to draft well should be on the bottom, other things equal.
<p>3. Subtle point that really doesn't matter at all: The way I've written my code does not abide by the strictest interpretation of Backwards Best Player Available. I do a slight reordering in cases where the best players available are also available at your next pick. This does not impact the optimal player portfolio or Perfect Draft Value, it just occasionally switches up a couple players in situations where it's irrelevant who you pick first. Literally, don't worry about this unless you plan on replicating these results manually.
<p>4. DM me (@nnstats) with questions/concerns/comments/ideas for extensions.</p>