---
layout: page
title: Assisting Researchers in the Use of ACI Resources
---

<a name="toc"></a>

1. [Introduction](#introduction)
2. [Establishing Communication Routes for Providing Assistance](#routes)
3. [Effective Communication in Assistance Interactions](#communication)
4. [Addressing User-Reported Issues](#issues)
5. [Assistance for Non-Issue Support Requests](#non-issue)
6. [Proactive Support](#proactive)
7. [Reflection on Assistance Experiences](#reflection)


<a name="introduction"></a>
<h2> Introduction</h2>

Assisting researchers as they actively use ACI is a key component of
facilitation, especially if the Facilitator is directly associated with
one or more specific ACI services, or when researchers require outside
resources. Whether researchers are already leveraging an ACI resource or
have just gained access, they should be be able to easily obtain ongoing
assistance from Facilitators and other ACI support staff with respect
to:

<ul>
<li>questions about ACI capabilities and use </li>
<li>requests for help with issues</li>
<li>needs for learning materials </li>
<li>requests for engagement consultations or other guidance for new ideas </li>
<li>obtaining assistance for external ACI resources</li>
</ul>

Therefore, an essential component of providing assistance is to
establish consistent and accessible routes by which users can obtain
assistance and to establish a set of effective communication practices.
As described later in this section, assistance communication should
strive to be as clear as possible, regardless of the assistance route,
and present solutions that advance a researcher’s own future
capabilities in using ACI resources. We also discuss the importance of
translating assistance experiences into improvements to learning
materials (see also [Education and Training of Researchers](06-education)) and into
optimization of ACI system capabilities to better meet researcher needs
(covered in [Interfacing with ACI Resource Providers](09-interface)).

For the purpose of distinguishing the information in this section from
that in Engaging Researchers, we define “assistance” as the one-to-one
or one-to-few support of researchers already accessing an ACI resource,
where the support pertains directly to their specific practices in using
that resource. Assistance may follow from an engagement, especially if
the engagement results in the researcher using ACI for the first time.
It is also important to note that some interactions with researchers may
be a combination of engagement and assistance, or may transition from
one to another. For example, assistance discussions lead to a
redefinition of the ACI Plan and/or the need for another ACI resources
is recognized. As described above, assistance routes are also an
important avenue by which a researcher may request a new engagement
meeting. Jump to: [top](#toc)

<a name="routes"></a>
<h2>Establishing Communication Routes for Providing Assistance</h2>

lorem ipsum

Jump to: [top](#toc)

<a name="communication"></a>
<h2>Effective Communication in Assistance Interactions</h2>

Jump to: [top](#toc)

<a name="issues"></a>
<h2>Addressing User-Reported Issues</h2>

Although the nature of issues reported by users of ACI resources will
vary significantly between resource type, the basic practical steps for
troubleshooting and problem-solving are fairly general: seek evidence,
diagnose, identify and test solutions or workarounds, and implement
and/or communicate solutions. Regardless of whether an issue is simple,
such as an easy-to-fix user error, or one which requires significant
effort from ACI staff, there are several basic steps for communicating
solutions and for capitalizing on assistance requests for teaching
opportunities. 

<h3>Clarify the User’s Problem </h3>

Assistance-providers may first need to interpret the researcher’s
reported problem by asking any clarifying questions and by stating the
problem back to the researcher before proceeding further. This step will
confirm the issue with the researcher and may train the researcher to
provide pertinent details of what they observe early on in future help
requests. If multiple problems were reported, or the Facilitator
perceives that there may be more than one issue at play, these should be
stated and addressed, separately.

<h3>Identify Issue(s) and Appropriate Solution(s)</h3>

After the user’s problem has been clarified, typical problem solving
steps can be followed to identify the source of the problem and to
evaluate solutions.  This process may require the involvement of other
ACI staff or further input from the researcher. First, evidence of the
issue should be identified with help from the researcher, perhaps by
examining user files, user-provided error messages or file contents,
and/or indicators in system log files and metrics. After determining the
reason for the issue, it may be necessary to reproduce it, depending on
the exact problem, context, and precedents, and to potentially involve
other ACI staff. If a solution is not immediately obvious, and/or
requires more work, it may be necessary to provide the researcher with
an update, in order to communicate a potential resolution timeline.

<h3>Communicate Next Steps to the User</h3>

After selecting a solution for the issue, the Facilitator should
communicate this solution to the researcher, making sure to clearly
describe steps for implementing the solution. The source of the issue
should be explained clearly in order to provide context for the
effectiveness of a chosen solution. When more than one solution may be
appropriate, the Facilitator should explain reasons for suggesting a
specific solution. It may also be appropriate, and will certainly
enhance the user’s own future capabilities, to prepare the researcher
for potential, related issues that might arise in the future.
Importantly, such discussion should still be limited to a scope that
will not overwhelm the researcher with too much information, and
suggesting a follow-up meeting may be beneficial to ensure the best,
stepwise progression for solving a complex issue.

The following is an example of the above practices in an email
communication with a researcher:

Example 1: Email from researcher regarding file transfer

~~~
------------------------ 
Hello, I tried to use ‘scp’ to copy data to my 
user directory on host1.org.univ.edu, but I get a “Permission denied”
error.  Is something wrong with my account? 
-John Scientist
------------------------ 
Hi John, Thank you for writing to us with this
question. In order to understand why your scp command isn’t working, can
you send me the exact command you’re using and the terminal output when
you run the command? From what I can tell, there doesn’t seem to be
anything wrong with your account, but we’ll figure out what’s not
working.

Thank you, 
Michelle Facilitator 
Research Computing Facilitator, CHTC
------------------------- 
Hi Michelle, Here are the lines from my
terminal: 
JohnDesktop:~ JohnSl$ scp myfile host1.org.univ.edu:/home/jscientist 
jscientist@host1.org.univ.edu's password: 
scp: /home/jscientist/myfile: Permission denied

-John 
------------------------ 
Hi John, 

Ah. I think I see what’s wrong.
When you use ‘scp’ from your desktop, the ‘scp’ program assumes that
you’ll be connecting as your Desktop username (“JohnS”) unless you
specify that your username on the server is different.  Our own guide
for file transfer has some examples explaining this behavior and other
scp features (org.univ.edu/guides/filetransfer.html), and there is even
more information online if you Google something like “scp guides”.

Here’s a command that should work for you: 
scp myfile jscientist@host1.org.univ.edu:/home/jscientist

Thank you, 
Michelle Facilitator 
Research Computing Facilitator, CHTC
------------------------ 
~~~

Jump to: [top](#toc)

<a name="non-issue"></a>
<h2>Assistance for Non-Issue Support Requests</h2>

Often, users may contact Facilitators to discuss questions about ACI
options, capabilities, and modes of use. Typically these questions
differ from assisting with issues in that the user hasn’t encountered a
specific difficulty in using an ACI system, but may instead have more
general, proactive questions that can be addressed with targeted
clarification and guidance, or for which existing education and training
materials will be sufficient.

Examples of non-issue requests can include: 

1. What is the best way to run software “X” on the compute system? 
2. How much data can I store? 
3. Does anything on campus support my ACI need for “X”? 
4. I’m about to start on a project and I wanted to ask about “X”.

When addressing such questions, a slightly different approach for
information exchange may be appropriate, as demonstrated in the below
steps, though the overall process is still very similar in some ways to
issue resolution. Some non-issue questions may actually lead to a true
engagement, where a more complex ACI plan can be discussed. However, the
progression to deciding an engagement is necessary would still follow
the first few steps below, and according to practices described in
[Engaging Researchers](03-engagement). As a clear demonstration, we provide two simple
examples of email communication for non-issue requests, though the same
ideas would apply within the context of other assistance route(s).

<h3>Understand the User’s Most-immediate Question(s)</h3>

After receiving a non-issue question from a researcher, it is important
to fully understand the researcher’s intent and the scope of information
they’re seeking, within the context of what the Facilitator already
knows about the researcher’s relevant ACI knowledge, as is demonstrated
in the following exchange:

Example 2: Email from Researcher regarding the use of research computing resources

~~~
------------------------
Hello,
How do I run Matlab on multiple processors?
-Jane Biologist
------------------------
Hi Jane,
Thank you for writing to us with this question. I believe this will be 
your first time running Matlab jobs at our center. Are you wondering how 
to run many Matlab jobs at once, where each might use a different processor, 
or how to run a single Matlab job that utilizes multiple processors? 

I can even help point you in the best direction if you can explain a bit 
about what your Matlab program is doing, in terms of your research, and how 
it is using input data? Additionally, how might this work expand for you 
in the future if you could get it running efficiently in our compute systems?

Thank you,
Michelle Facilitator
Research Computing Facilitator, CHTC
-------------------------
Hi Michelle,
I would like to run my Matlab script that simulates genetic variability at 
least 1000 times, where each simulation uses the same genetic variation file 
and a unique set of parameters from my parameter file. This many simulations 
would take more than a week on my Mac, and I know that Matlab can be run on 
clusters using multiple processors at once, so that all 1000 simulations run 
faster. How many processors can I use for running this Matlab program on 
cluster A? Eventually, I’ll want to do the same for several different genetic 
starting points (variation files).
-Jane
--------------------------
~~~ 
(continued later...)


<h3>Anticipate the Real and Next Questions</h3>

In some cases, the original question(s) may be limited by the
researcher’s current knowledge of ACI such that the researcher is
actually seeking an answer to a slightly different question; or such
that the researcher’s goals can be best addressed by a different
solution than originally suggested. Additionally, the Facilitator may be
able to anticipate and answer other questions in order to reduce the
amount of back-and-forth communication. Inviting a transition to an
in-person meeting – perhaps more similar to an engagement – may even be
a more appropriate solution for assisting the researcher.

Example 2: (continued)

~~~
------------------------
Hi Jane,
Thank you for the additional information. Based upon what you’re 
describing, I believe you can accomplish more by running many separate 
Matlab jobs that each use a single processor, instead of being 
limited by how many processors a single Matlab job can run on. Our 
cluster B is ideal for this type of high-throughput computing (HTC) work, 
and you will likely find that you could easily run more simulations with 
more parameters than on our Cluster A; you’ll also be able to repeat that 
many simulations for the different genetic starting points you describe.

As you might imagine next, this approach will mean that you will want to 
slightly rework your Matlab program a bit to read in a single parameter file, 
each time, in addition to reading in the genetic file. So you’ll also want 
to pre-create separate parameter files that each only have the relevant 
parameters for a single simulation. Let me know if you’d like pointers 
in Matlab’s documentation on how to read in the files or ideas for breaking 
up a parameter file.

Our own online guides for how to set up and submit many single-processor 
Matlab jobs is here: www.compute-center.school.edu/htc-matlab-jobs

Let me know if you have any questions about the above information.
 We can always meet to discuss more, if you like. ‘Sound good?

Michelle
--------------------------
~~~

<h3>Empower the User to Find Her/His Own Answers</h3>

As demonstrated in the facilitator’s response above, it is important to
link to external resources that contain solutions for achieving a
researcher’s goals. This practice is not only important for providing
next steps, but also demonstrates how one might find answers to such
questions more quickly in the future, as was hinted in the prior
example. Another example of these practices is provided below:

Example 3:  Email from researcher regarding command-line text editors

~~~
Hello,
I have been using the nano text editor on the cluster servers, but I hear 
that other text editors have more options. Which text editor would you suggest?
-Zoe Chemist
------------------------
Hi Zoe,
My personal favorite for the command-line is the ‘vim’ text editor, which 
is on just about Linux server. You can certainly find a number of online 
tutorials in various formats, by searching online for “vim text editor guide”. 
You can also find many online comparisons of text editors beyond ‘vim’ by 
searching for something like “which command line text editor is best?”. There 
are heated debates, and most people who use the command line have strong 
preferences, but the information you find will likely help you decide which 
text editor you might prefer. I prefer ‘vim’ (sometimes referred to as ‘vi’) 
because it is more powerful than ‘nano’, with a moderate number of standard 
options. I’d be happy to discuss more, if you like.

Cheers,
Michelle Facilitator
-------------------------
~~~

While it should always be the goal of a Facilitator to enable
researchers to do more for themselves, indicating how a researcher can
find her/his own answers should not be intended to discourage the
researcher from seeking assistance from Facilitators and other staff.
Facilitators need to find a balance between empowering researchers to
learn to find their own answers while still welcoming future assistance
requests, as needed.

Jump to: [top](#toc)

<a name="proactive"></a>
<h2>Proactive Support</h2>

Proactive user support can be thought of as assistance initiated by the
Facilitator rather than by a user of an ACI resource. It might be
helpful to the researcher when a Facilitator occasionally checks in, not
only when indications of difficulty become apparent (in user metrics,
for example), but also to understand how a researcher’s use and
satisfaction of ACI may have evolved. Often, but not always, proactive
assistance may even evolve into conversations more akin to engagements.

This particular activity is perhaps the most important component
distinguishing the facilitation approach from more common approaches of
supporting users of CI, whereby researchers are provided with written
documentation and are left to initiate contact with facilitators.
Proactive assistance allows Facilitators to build upon relationships
with researchers and, more importantly, to identify issues that users
may not think to ask about.

A few possible reasons to proactively contact a user are:

1. Metrics indicate misuse of an ACI resource. 
2. Metrics indicate that a user’s work may be better optimized. 
3. A sudden increase in the user’s activity potentially indicates a new type of work with different resource needs to address. 
4. The Facilitator believes a follow up to previous assistance may be helpful. 
5. The Facilitator may simply want to check in with a long-time user who hasn’t written in with any issues in some time.

If the reason for contacting the researcher is more akin to issue
resolution or proposing enhancements to the researcher’s use of ACI, the
Facilitator will likely follow assistance communication steps as
described in previous topics of “Addressing User-reported Issues” and
“Assistance for Non-issue Support Requests”. However, simple follow-ups
regarding the researcher’s assessment of ACI resources and services,
his/her evolving research goals, or simply to see how things are going
will likely follow more of a casual interview. If the Facilitator has
specific goals in contacting the researcher, preparing a set of specific
questions will be helpful. More information on understanding researcher
attitudes using interview-like interactions is available in 
[Assessment and Metrics](10-assessment).

Jump to: [top](#toc)

<a name="reflection"></a>
<h2>Reflection on Assistance Experiences</h2>

Jump to: [top](#toc)
