# My Network Has Commitment Issues: AI Debugged Its Feelings

**<a href="https://secdsm.org/" target="_blank">SecDSM</a> Talk - December 2025**

Networks promise reliability but ghost you at 3 AM. I got tired of reading logs, so I taught AI to be my troubleshooting partner.

This repo has everything from the talk.

## What's Here

**[Slides (PDF)](slides.pdf)** — The full deck. Network therapy jokes included.

**Demos** — All four live demos, uncut:

1. **<a href="https://www.youtube.com/watch?v=TnXcstMX6Po&list=PLkqpKepgEfOvAX0dvq_37jrLoNvXFsbxv&index=1" target="_blank">C2 Detection Demo</a>** — AI finds beaconing behavior in a 1.6GB PCAP. DNS tunneling, C2 server, the works.

2. **<a href="https://www.youtube.com/watch?v=3s428jQI32c&list=PLkqpKepgEfOvAX0dvq_37jrLoNvXFsbxv&index=2" target="_blank">Linux Compromise Demo</a>** — That Raspberry Pi that "just needs a reboot"? Yeah, it was owned. AI caught it.

3. **<a href="https://www.youtube.com/watch?v=5uVPq2Tciug&list=PLkqpKepgEfOvAX0dvq_37jrLoNvXFsbxv&index=3" target="_blank">VPC Finding Demo</a>** — Security asks "What's this IP doing?" AI maps the entire VPC flow in 2 minutes.

4. **<a href="https://www.youtube.com/watch?v=WQ2INT4s4Uw&list=PLkqpKepgEfOvAX0dvq_37jrLoNvXFsbxv&index=4" target="_blank">VPC Flow Log Analysis</a>** — 100,000 lines of flow logs. Planted exploits. AI finds them all and writes the incident report.

**[Full Playlist](https://www.youtube.com/watch?v=TnXcstMX6Po&list=PLkqpKepgEfOvAX0dvq_37jrLoNvXFsbxv" target="_blank">Full Playlist</a>** — All demos in one place.

## AI Personas

The actual prompts I used in the demos:

- **[Network Operations Agent](personas/Network%20Operations%20Agent%20Persona.md)** — VPC flow log analysis, network mapping, security group tracing
- **[Threat Hunter Agent](personas/Threat%20Hunter%20Agent%20Persona.md)** — PCAP analysis, C2 detection, incident response

These are the real 150+ line prompts with detailed instructions, context, and formatting rules.

## The Point

You don't have time to read all the data your network generates. SNMP, syslog, NetFlow, VPC flow logs, packet captures — it's screaming at you faster than you can process it.

AI reads faster than you, never gets bored, and spots anomalies while you're still booting your laptop.

It's not a replacement. It's a partner.

## Memes

Because network troubleshooting needs more humor:

![You are the log parser](images/human-log-parser.png)  
*Congratulations. You're the most expensive log parser in the building.*

![What's this IP doing?](images/whats-this-ip.png)  
*Every network engineer has gotten this message. Usually at 4 PM on a Friday.*

## Want More?

I wrote a <a href="https://fugate.dev" target="_blank">full blog post</a> about this with the practical how-to guide, real examples, and lessons learned (including the time AI `rm -rf`'d my data directory).

## Questions?

Hit me up. I'm happy to talk about AI, networking, or how to secure your Raspberry Pi.

And remember: **Be polite to the AI. You never know what's coming.**

## License

This work is licensed under [CC BY 4.0](LICENSE). Use it, remix it, share it — just give credit and link back to <a href="https://fugate.dev" target="_blank">fugate.dev</a>.
