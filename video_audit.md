# Video Audit — Playlist Census

Source playlist: [MCP-youtube](https://www.youtube.com/playlist?list=PLyzTA8cetPdHtlGw1X8Kt7Ea4bd27ApR7)

- Total videos in playlist: 52
- ML/AI tech videos (kept): 9
- Non-ML videos (excluded): 31
- Unresolved (unavailable/private/deleted): 12

(9 + 31 + 12 = 52)

The 9 kept ML/AI tech videos are the ones that produced entries in `ml_tech.md` and
`exceptions.md`; they are not re-listed here.

## Non-ML videos (excluded) — 31

1. **The Strange Math That Predicts (Almost) Anything** — https://www.youtube.com/watch?v=KZeIEiBrT_w — Math explainer (Veritasium) on the history of Markov chains and probability; no ML technology covered.
2. **Learning Software Engineering During the Era of AI \| Raymond Fu \| TEDxCSTU** — https://www.youtube.com/watch?v=w4rG5GY9IlA — General TEDx talk on how AI changes learning software engineering; discusses no specific ML/AI technology.
3. **World's Fastest Car Vs Cheetah!** — https://www.youtube.com/watch?v=FWAdfuPpLOc — Entertainment/automotive challenge video (MrBeast); no ML content.
4. **iOS 26: Introducing Liquid Glass** — https://www.youtube.com/watch?v=jGztGfRujSE — Apple OS design/feature announcement; consumer software UI, not ML.
5. **Amazon 4k : The Breathtaking Journey Into Amazon Rainforest \| Nature's Green Paradise** — https://www.youtube.com/watch?v=Wa9wv5qV1Uk — Nature documentary footage; no ML.
6. **Inside a Real High-Frequency Trading System \| HFT Architecture** — https://www.youtube.com/watch?v=iwRaNYa8yTw — Low-latency trading-systems architecture (networking/C++); not ML.
7. **My first week as a big tech software engineer in New York** — https://www.youtube.com/watch?v=VBSf1e9uMdw — Career vlog; no ML.
8. **SQL Full Course for Beginners (30 Hours) - From Zero to Hero** — https://www.youtube.com/watch?v=SSKVgrwhzus — SQL/database tutorial; not ML.
9. **How To Use GitHub For Beginners** — https://www.youtube.com/watch?v=a9u2yZvsqHA — Git/GitHub usage tutorial; not ML.
10. **When Nanoseconds Matter: Ultrafast Trading Systems in C++ - David Gross - CppCon 2024** — https://www.youtube.com/watch?v=sX2nF1fW7kI — CppCon talk on low-latency C++ trading systems; not ML.
11. **Day in the Life of an MIT Computer Science Student** — https://www.youtube.com/watch?v=bhQ7VVZqGSQ — Student lifestyle vlog; no ML.
12. **Why Applications Are Operating-System Specific** — https://www.youtube.com/watch?v=eP_P4KOjwhs — Operating-systems concepts explainer; not ML.
13. **Probability and Statistics: Overview** — https://www.youtube.com/watch?v=sQqniayndb4 — Statistics lecture (Steve Brunton); math foundations, not an ML technology.
14. **Welcome to Carnegie Mellon, Class of 2028** — https://www.youtube.com/watch?v=kGiaKTHmfyE — University welcome video; no ML.
15. **How to write an okay research paper.** — https://www.youtube.com/watch?v=qNlwVGxkG7Q — Academic-writing advice talk (Sasha Rush); not ML.
16. **Day in the Life of a Data Scientist in San Francisco** — https://www.youtube.com/watch?v=T1QOf1GfGuI — Day-in-the-life vlog about the data-science job; no ML technology covered.
17. **Pain physiology mbbs 1st year, pain pathways, endogenous pain relief system** — https://www.youtube.com/watch?v=r8ForU8slWk — Medical physiology lecture; no ML.
18. **Convert Fluorescent Tube Lights to LED - Easy Ballast Bypass Instructional** — https://www.youtube.com/watch?v=zc-29W_p1M4 — Electrical/hardware how-to; no ML.
19. **But what is a convolution?** — https://www.youtube.com/watch?v=KuXjwB4LzSA — 3Blue1Brown math explainer on the convolution operation; math foundation for ML, not an ML technology.
20. **Day in the Life of a Data Science Student at UC Berkeley** — https://www.youtube.com/watch?v=hREfleo04GE — Student lifestyle vlog; no ML.
21. **Olympiad level counting (Generating functions)** — https://www.youtube.com/watch?v=bOXCLR3Wric — Competition-math lecture on generating functions; no ML.
22. **I Dropped Computer Science at CMU: Here's Why** — https://www.youtube.com/watch?v=ykC3vb9K8a8 — Personal/career story; no ML.
23. **UC Berkeley Campus Tour: World's Best Public University** — https://www.youtube.com/watch?v=-5XxqW9Z7PI — Campus tour video; no ML.
24. **STM32 Guide #1: Your first STM32 dev board** — https://www.youtube.com/watch?v=rfBeq-Fu0hc — Embedded-electronics tutorial; no ML.
25. **Top 10 IoT Projects 2026 \| Useful IoT Devices \| Smart IoT Projects \| IoT Applications** — https://www.youtube.com/watch?v=N_z4OaSuoAA — IoT project roundup; not ML.
26. **IoT \| Internet of Things \| What is IoT ? \| How IoT Works? \| IoT Explained in 6 Minutes** — https://www.youtube.com/watch?v=6mBO2vqLv38 — IoT concepts explainer; not ML.
27. **Taylor Swift - august (Official Lyric Video)** — https://www.youtube.com/watch?v=nn_0zPAfyo8 — Music video; no ML.
28. **Bayes theorem, the geometry of changing beliefs** — https://www.youtube.com/watch?v=HZGCoVF3YvM — 3Blue1Brown math explainer on Bayes' theorem; math foundation, not an ML technology.
29. **My Life At The #1 CS College in the US: Carnegie Mellon** — https://www.youtube.com/watch?v=nyHnU123Iew — Student lifestyle vlog; no ML.
30. **How to Speak** — https://www.youtube.com/watch?v=Unzc731iCUY — MIT lecture on public speaking and presentation technique; not ML.
31. **How I Became a Software Developer @ GitHub - Brooks Swinnerton** — https://www.youtube.com/watch?v=ESd5Nt8sHE0 — Developer career-story interview; no ML.

## Unresolved (12)

The playlist's own header reports **52 videos**, but YouTube's playlist listing only renders the
first **40** entries (playlist positions 1–40, indices 0–39). The listing terminates after
position 40 with no continuation token, so the remaining **12 entries (playlist positions
41–52)** are never rendered at all. That is the signature of entries whose videos have been
deleted, set to private or otherwise made unavailable: the current playlist page silently drops
them instead of showing "[Deleted video]" / "[Private video]" placeholder rows.

Nothing beyond their position in the playlist is visible for these 12 entries — no title,
channel, URL or video ID is exposed — so their content is deliberately not guessed at here:

- Playlist positions 41–52 (12 entries): unavailable/private/deleted — no metadata visible.
