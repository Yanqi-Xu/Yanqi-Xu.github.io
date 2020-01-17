---
name: Accountability Project
tools: [R]
image: 
description: I am a data reporter for the Investigative Reporting Workshop's Accountability Project. 
---
### What's the point?
Say you are on deadline and come across an organization and you wish to run a search to see its background. Campaign finance, business licenses, lobbying registration, public employees' salaries... You know where to look, but you will be under a crunch to look for all the data going to different websites and trying to keep your tabs under control. Sometimes there are various spellings of the same address and you need to try multiple times to get the match in the query database?

Your local agency may not collect the data, but you might find more information from a federal agency. And before you go there and look, it's hard for you to find out.

Enter the [Accountability Project](https://www.publicaccountability.org/). We curate various datasets of public records and centralize them.
You wouldn’t need to go on different websites and navigate various query pages or download several whole datasets. The Accountability Project will tell you where the name and organization you’re searching for gets hits.

### Where do we get the data?
Most of the time, we use the scripting language R to download the data and save it into our environment. 
But we also request, scrape html tables and parse PDFs too.
### What do we do with it?
We developed an R package [`campfin`](https://github.com/irworkshop/campfin) to clean and normalize city names, ZIP codes and phone numbers. It enhances searchability and return more accurate results when you need to use services like Geocoding. We also make public our package's data cleaning algorithms to normalize fields on GitHub so that we have our fair share of accountability.

<p class="text-center">
{% include elements/button.html link="https://github.com/irworkshop/accountability_datacleaning/blob/master/R_campfin/wi/lobbyists/docs/wi_lobby_exp_diary.md" text="Check out the Wisconsin Lobbying Expenditure Data Diary" %}
</p>