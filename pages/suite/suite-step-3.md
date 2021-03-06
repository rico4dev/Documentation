---
title:  "Step 3: First Impression"
summary: The node server runs the system on the console and the browser runs the web application functioning as a user interface.
sidebar: suite_sidebar
permalink: suite-step-3.html
toc: false
---

Once you fire up the system, *things* start happening on the console and the browser...

## On the Console

Node JS runs several servers&mdash;the server-side of the system&mdash;on the same console window. A few seconds later, bots are fired up to start fetching data from the exchange, as well as processing candles and a few basic indicators.

{% include image.html file='how-to/run-the-system-01.gif' url='yes' max-width='100' caption='Several servers are started after running the ```node run``` command. Moments later, bots start logging their activity.' %}

{% include note.html content="The console must be open for as long as the system is running. Feel free to minimize it, but keep in mind it will later display valuable information." %}

## On the Browser

The system opens your default browser and loads the web application that functions as a user interface. 

{% include tip.html content="You should either <a href='https://support.google.com/chrome/answer/95417?co=GENIE.Platform%3DDesktop&hl=en' rel='nofollow' rel='noopener' target='_blank'>set Chrome as your default browser</a> before firing up the system, or simply close the non-Chrome browser, open Chrome, and go to <a href='http://localhost:34247/' rel='nofollow' rel='noopener' target='_blank'>http://localhost:34247/</a>." %}

{% include image.html file='how-to/run-the-system-02.gif' url='yes' max-width='100' caption='The dark side of the web application is the design space. Pull the slider up and you will find the charting space. In the beginning, all charts are empty.' %}

## Congratulations! 

You are up and running!

Now you are ready to learn the basic operation of the system. You will learn how to browse markets, run a first backtest, and try a live trading session, to get the feel for how things work.

{% include note.html content="How much time it takes for historic data to be retrieved from exchanges, processed, and rendered on the charts depends on several things, including your machines' [processing power](suite-system-requirements.html#processing-power). Expect to see the first few candles populating the charts 20 to 40 minutes after firing up the system." %}
