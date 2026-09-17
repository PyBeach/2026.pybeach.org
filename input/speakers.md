# PyBeach 2026 Speakers and Program

Here is the set of speakers we have selected for our 2026 program. Note that this list may be subject to change due to extenuating circumstances such as speaker availability. For full details of when each talk will take place, see our [schedule page on pretalx](https://pretalx.com/pybeach2026/schedule/).

# Andrew Annex, Ph.D. {#annex}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/AHKBJB_fXucRwR.webp" alt="Andrew Annex" class="speaker-image">
    <div class="speaker-bio">
      <p>
        Andrew Annex, Ph.D. is a senior SWE at Planet Labs and a planetary scientist at the SETI Institute. He has maintained SpiceyPy, an open source Python library, for over a decade.
      </p>
    </div>
</div>

## Talk: **Accessing NASA Planetary Ephemeris with SpiceyPy** [(schedule)](https://pretalx.com/pybeach2026/talk/9GUT89/)

<div class="talk-abstract">
Learn how to access NASA planetary mission ephemeris data with SpiceyPy; a community-developed open source wrapper to the JPL SPICE toolkit.
</div>

# Christopher Neugebauer {#neugebauer}

<div class="speaker-container">
    <img src="https://pretalx.northbaypython.org/media/avatars/V37K3L_ZV7NmZD.jpg" alt="Christopher Neugebauer" class="speaker-image">
    <div class="speaker-bio">
      <p>
Christopher Neugebauer is an Australian developer, speaker, and serial community conference organiser, who presently lives in the United States.

He serves as a Director of the Python Software Foundation, and is co-organiser of the acclaimed North Bay Python conference, a boutique one-track conference run in unusual venues — include an old vaudeville theatre, and more recently a barn on a farm — in Petaluma, California.
      </p>
    </div>
</div>

## Talk: **Adventures in GIL-Free Python (finally!)** [(schedule)](https://pretalx.com/pybeach2026/talk/XFTA7W/)

<div class="talk-abstract">
For the first time in the history of (stable) CPython, there’s options for concurrent processing in the same process: the GIL isn’t gone, but in select situations, you can definitely avoid it. 

CPython’s global interpreter lock made CPython simple to implement and fast enough for most purposes, at the expense of threads (mostly) not being able to run in parallel. While this was fine for many people, it did keep a large number of problem spaces inaccessible to people using CPython.

Over the past few decades, brave maintainers embarked on many efforts to remove the GIL from CPython, but until recently, they all resulted in undesirable complexity in the interpreter and unacceptable slowdowns in single-threaded code. But recently, there’s been meaningful progress!

Starting with Python 3.14, there’s two ways to enjoy GIL-free Python: Subinterpreters have had independent GILs for a number of releases now, but without a good way to access them from within Python itself. Subinterpreters now have a Python-accessible API and they unlock Communicating Sequential Processes-style concurrency (like Go channels) without the overhead of entire new processes (like you have to with Python `multiprocessing`).

And more excitingly, there’s now free-threaded Python: Python can now be optionally built without a GIL, at the expense of a very slight slowdown in single-threaded code. Free threading requires specialised builds and isn’t the default (because it’s slower), but if you need actual threaded concurrency, the option is now there for you.

In this talk, we’ll look at the state of concurrent execution in Python: how to use both GIL-free options, how they compare to existing options, and what new workloads are now realistic to solve in Python. Slowly but surely, Python is getting faster. Find out how you can take advantage of it!
</div>

# Trey Hunner {#hunner}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/UYHZBE_5M4kX61.webp" alt="Trey Hunner" class="speaker-image">
    <div class="speaker-bio">
      <p>
Trey Hunner is a Python Software Foundation Fellow, former PSF Director, one of the founding members of the PSF Code of Conduct workgroup, and a semi-regular attend of his local Python meetup in San Diego.

Trey specializes in Python education and corporate training. You can learn from Trey through <a href="https://www.pythonmorsels.com/newsletter/">his weekly Python tips newsletter</a> and his <a href="https://www.pythonmorsels.com/">Python Morsels</a> learning platform.
      </p>
    </div>
</div>

## Talk: **Everything You Don't Need to Know About Classes in Python** [(schedule)](https://pretalx.com/pybeach2026/talk/8RNAEW/)

<div class="talk-abstract">
What happens when you look up an attribute on a Python object? And how do methods actually work?

You don't need to understand *most* of Python's many class features in order to write object-oriented Python. But understanding classes more deeply *can* be helpful!

During this talk we'll expand our mental models of Python's classes by peeling back the layers behind Python's many class features. Along the way we'll take a brief tour through dunder methods, descriptors, metaclasses, and more.

It's time to get classy.
</div>

# Noah Kantrowitz {#kantrowitz}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/MY7QMZ_y0OB8S3.webp" alt="Noah Kantrowitz" class="speaker-image">
    <div class="speaker-bio">
      <p>
Noah Kantrowitz is a web developer turned infrastructure automation enthusiast, and all around engineering rabble-rouser. By day he runs infrastructure at Geomagical/IKEA and by night he makes candy and stickers. He is an active member of the DevOps community, and enjoys merge commits, cat pictures, and beards.
      </p>
    </div>
</div>

## Talk: **I am bad at things – And that’s okay** [(schedule)](https://pretalx.com/pybeach2026/talk/VVAM7B/)

<div class="talk-abstract">
Humans make mistakes. We all know it, and yet so often downplay this in our team processes. Doubly so in this age of assuming we’ll always notice the errors from AI and automation in code review. One of the marks of a good system is how it handles our inherent human fallibility. This talk will discuss how cognitive biases create common failure modes, principles for building resilient systems through checklists and objective measurements, and how all of this affects us as individuals. As we are asked to move faster and faster, relying on permanent hyper-vigilance leaves an increasing and worrying burden on us all.
</div>

# Bernát Gábor {#gabor}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/EGPZKP_2LJUDs4.webp" alt="Bernát Gábor" class="speaker-image">
    <div class="speaker-bio">
      <p>
Software engineer at Bloomberg. Primary maintainer of tox, virtualenv, build, pipx, filelock, and platformdirs. Regular speaker at PyCon US, EuroPython, PyTexas, and PyLondinium since 2018. <a href="https://bernat.tech/about/">https://bernat.tech/about/</a>
      </p>
    </div>
</div>

## Talk: **Securing Your Python Supply Chain: From Dependencies to Deployment** [(schedule)](https://pretalx.com/pybeach2026/talk/9BUFWV/)

<div class="talk-abstract">
Supply chain attacks targeting Python packages hit real projects with millions of users. The Ultralytics compromise injected a cryptocurrency miner into a package with 80 million monthly downloads. GhostAction stole 3,300+ secrets from 570+ repositories. The Shai-Hulud worm crossed ecosystem boundaries from npm to PyPI. These attacks exploited gaps that most Python developers leave open: unpinned dependencies, long-lived API tokens, no vulnerability scanning.

Your average Python project pulls in dozens of transitive dependencies you never chose. pip install flask gives you seven packages. If any one of them gets compromised, your application is vulnerable.

You can defend against these with tools available today. Ruff catches security bugs (hardcoded secrets, weak crypto, missing timeouts) before code leaves your editor. uv generates lockfiles with cryptographic hashes that detect tampering. pip-audit flags known CVEs in CI before they reach production. CycloneDX SBOMs let you answer "are we affected?" in minutes when the next compromise drops. Trusted Publishing eliminates long-lived PyPI tokens using short-lived OIDC credentials. Delayed ingestion with --exclude-newer gives the community time to spot malicious packages before you install them.

The session provides a phased adoption roadmap: start with linting and pinning for quick wins, add scanning and SBOMs next, then scale to advanced defenses as your security posture matures. All levels welcome.
</div>

# Elizabeth Bacon {#bacon}

<div class="speaker-container">
    <!-- <img src="" alt="Elizabeth Bacon" class="speaker-image"> -->
    <div class="speaker-bio">
      <p>
Elizabeth Bacon teaches middle school computer science at Wildwood School. A former school administrator and course developer, she is happy to be back in the classroom, watching students express their creativity through games, apps and physical computing projects. She's active in the CS educator community, presenting at conferences and serving on various committees to promote and support K-12 computer science education.
      </p>
    </div>
</div>

## Talk: **Supporting the Next Generation of Pythonistas** [(schedule)](https://pretalx.com/pybeach2026/talk/JG99ST/)

<div class="talk-abstract">
Computer science education is a world of contradictions. Computing increasingly mediates every aspect of our lives, just as young people are told that programming will soon be obsolete. Classical funding sources have dried up while money for "AI education" is seemingly endless. This session will cover the overall landscape of CS education, while diving into the concrete realities of teaching within it. We'll look at how teachers are addressing the current challenges and helping students to build the cognitive skills necessary to design, develop and maintain software in a collaborative environment. Along the way, we'll showcase some student work in steganography, robotics, and CS research from a local school.
</div>

# Margaret Fero {#fero}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/CNH39T_Hg3xbBK.webp" alt="Margaret Fero" class="speaker-image">
    <div class="speaker-bio">
      <p>
Margaret Fero is an interdisciplinary hacker who enjoys systems thinking, information flow, security, privacy, books, words, and the Internet. They are the founder of Neat Systems, a member of the NumFocus Code of Conduct Working Group, a cybersecurity and AI instructor, a member of the Alameda County Library Advisory Commission, and more! They also love to build healthy and inclusive working environments using research-backed management practices.
      </p>
    </div>
</div>

## Talk: **Technical Documentation in the Age of LLMs** [(schedule)](https://pretalx.com/pybeach2026/talk/XUQ8EW/)

<div class="talk-abstract">
Whether or not you’re using Claude, Codex, or other tools being sold as “AI-powered coding assistants”, many of your users are. The most recent (2025) StackOverflow developer survey found that 79% of respondents were using AI tools at least monthly, and more than half of early-career and mid-career devs reported daily use. Those same early- and mid-career devs are often your documentation users, though often less-directly than they have been in the past. When users aren’t actually looking at your documentation as you presented it, how can you facilitate their discovery of the information they need? In this talk, we’ll cover some longstanding best practices and their role in the current documentation use landscape.

This is not a talk about how to use LLMs, but a talk about how to write universally-helpful docs that work just as well for LLM users.
</div>

# Barbara Shaurette {#shaurette}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/GBNNSD_FKYuY1z.webp" alt="Barbara Shaurette" class="speaker-image">
    <div class="speaker-bio">
      <p>
Barbara Shaurette is a senior SRE and data infrastructure engineer with nearly 25 years of experience building and maintaining production systems. As a longtime member of PyLadies and the Python community, she's passionate about teaching and about using the right tool for the job. She blogs (infrequently) at <a href="https://mechanicalgirl.com">mechanicalgirl.com</a>.
      </p>
    </div>
</div>

## Talk: **The Small Web Doesn't Need Big Analytics** [(schedule)](https://pretalx.com/pybeach2026/talk/78BZAW/)

<div class="talk-abstract">
The indie web is making a comeback. People are building personal sites, small apps, and passion projects again, and they deserve infrastructure that matches that scale. But when it comes to knowing who's visiting your site or keeping bots at bay, the default advice is always "just use [expensive SaaS tool]." Google Analytics for visitor counts. Cloudflare for bot blocking. Tools built for enterprises, billing like enterprises.

There's a better way. In this talk, we'll walk through a lightweight traffic tracking and bot-blocking solution written in pure Python. All you need are a small database table, the `ua-parser` library, and a middleware pattern that works equally well in Flask, Django, or any other Python web framework. You'll leave with a practical, self-hosted solution you can drop into any Python-based web project, and a renewed appreciation for how much you can do without reaching for your credit card.
</div>

# Andrew Godwin {#godwin}

<div class="speaker-container">
    <img src="https://pretalx.com/media/avatars/TNSFVY_2a76k7R.webp" alt="Andrew Godwin" class="speaker-image">
    <div class="speaker-bio">
      <p>
Andrew has been writing software, and Python and Django especially, for rather too long, and enjoys working on overall architectural and system design problems, as well as being a little too interested in weird datastore patterns. He is currently the overall technical lead for Lambda.ai's cloud platform.

In his spare time, he enjoys rescuing people having a bad day in the mountains, flying light aircraft, making strange art in his workshop, trying new and interesting kinds of cheese, and trying not to gather more hobbies.
      </p>
    </div>
</div>

## Talk: **Working With Risk: Lessons From Mountain Rescue** [(schedule)](https://pretalx.com/pybeach2026/talk/QR8ZYT/)

<div class="talk-abstract">
We'd all like to completely avoid risk, but that's often not an option - so rather than ignoring it, how do we acknowledge it and work with it head-on?

We'll draw from a world where risk is ever-present and very high stakes - mountain rescue - and see what we can take from managing life-safety in a hostile environment and apply it to how we develop teams, companies, and systems.

Content warning: Occasional references to death, but no explicit details or stories.
</div>
