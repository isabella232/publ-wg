---
layout: default
---

# Information on Meetings
{: .no_toc}

* TOC
{:toc}

## Teleconferences

The weekly teleconferences are held _every week on Mondays_, at *noon US Eastern time* (see the [time zone calculator](https://goo.gl/ujkGY1) for the exact timing for your time zone). See the [separate page](./gotomeetings) for the dial-in information.

The Group also uses IRC for during the calls for minute taking, queue control, and general chit-chat. See the [separate page at W3C](https://www.w3.org/Project/IRC/) for further details. This Working Group uses the `#pwg` channel, and makes use of two bots on IRC:

* `zakim` for queue control (see the separate [manual pages](https://www.w3.org/2001/12/zakim-irc-bot.html) for  further details.)
* `rrsagent` for scribing and minute generation (see the separate [manual pages](https://www.w3.org/2002/03/RRSAgent) on how to control the access rights and storage of the IRC logs, and the separate [`scribejs` features](https://github.com/w3c/scribejs/blob/master/features.md) for the scribe instructions).


## F2F meetings

* [September 16-17, 2019, Fukuoka, Japan](./F2F/2019.09.Fukuoka)
* [May 6-9, 2019, Cambridge, MA, USA](./F2F/2019.05.Cambridge)
* [October 22-23, 2018, Lyon, France](./F2F/2018.10.Lyon)
* [May 30-31, 2018, Toronto, Ontario, Canada](./F2F/2018.05.Toronto)
* [November 6-7, 2017, Burlingame, CA, US](./F2F/2017.11.Burlingame)
* [June 22-23, 2017, New-York, NY, USA](./F2F/2017.06.NYC)

## Meeting Minutes

Meeting minutes (both for F2F and telcos) are listed [separately](./Minutes/).

### Minute taking

Minutes are taken using IRC, and is based by a collective effort: one of the participants should be the scribe for (part of) a session. The `rrsagent` bot is used to archive the IRC log at the end of the call, and a separate tool (called [`scribejs`](https://github.com/w3c/scribejs/)) is used to generate the cleaned-up minutes that are published on the Working Group’s Web site.

Minute taking and cleanup is greatly helped by:

* the scribe should used a number conventions, documented [`scribejs` features](https://github.com/w3c/scribejs/blob/master/features.md) separately.
* to help minute taking and cleaning them later, please use a consistent IRC handle; scribes should use that handle to identify the person speaking. `scribejs` automatically replaces the handle with the person’s full name, making the minutes more readable to outsiders.
    * note that in most IRC clients the `TAB` key can be used to expand to an existing irc handle

* *Each participant should type `present+ <name>` (or simply `present+` for himself/herself) in the irc channel immediately upon joining the call.* (This will help the minute taker and improve the generated minutes.)

### Updating the minutes

The minutes themselves are stored, in Markdown (more exactly in “Kremdown”) on the WG’s core [github repository](https://github.com/w3c/publ-wg) in the `Meetings/Minutes/2017`, `Meetings/Minutes/2018`, etc., folders.

As described in the [separate page on our working mode](../WorkMode/index#telco), meeting minutes are considered as “Draft” until officially approved after five business days, usually at the subsequent meeting. During that period, if a participant requests a change in the minutes, he/she can issue, for example, a Pull Request with the proposed changes.
