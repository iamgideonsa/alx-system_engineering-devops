# `0x19. Postmortem`
A project done during **ALX SE Studies** at **ALX School**.

## `Background Context`
`https://youtu.be/rp5cVMNmbro?si=6-GB6llNcxa_gDY0`
Any software system will eventually fail, and that failure can come stem from a wide range of possible factors: bugs, traffic spikes, security issues, hardware failures, natural disasters, human error… Failing is normal and failing is actually a great opportunity to learn and improve. Any great Software Engineer must learn from his/her mistakes to make sure that they won’t happen again. Failing is fine, but failing twice because of the same issue is not.

A postmortem is a tool widely used in the tech industry. After any outage, the team(s) in charge of the system will write a summary that has 2 main goals:
* To provide the rest of the company’s employees easy access to information detailing the cause of the outage. Often outages can have a huge impact on a company, so managers and executives have to understand what happened and how it will impact their work.
* to ensure that the root cause(s) of the outage has been discovered and that measures are taken to make sure it will be fixed.

#
![](https://i.imgflip.com/7f2140.jpg)

<div align="center">
  <h1>Postmortem: Web Stack Outage 😱</h1>

  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROHD9epLsedok1E8iv-AjG1T-ZDPDlm6C_tzGjmTJ8XQ&s" alt="Comic" width="400" height="200">
</div>

## `Issue Summary:`
- **Duration:** *October 7, 2023, 10:00 AM - October 7, 2023, 11:30 AM (UTC)*
- **Impact:** 🙀 Oh, the horror! Our primary web application took a coffee break. Around *80%* of users had to sip extra coffee as they faced slow response times, intermittent errors, and the urge to start a support group for frustrated users.
- **Root Cause:** 🤯 The servers threw a party and invited everyone - a surge in traffic gave our database servers a headache, causing them to stutter and stall.

## `Timeline:`
- **10:00 AM (UTC):** 🚨 Our monitoring system woke up from its nap, panicked about high server response times.
- **10:05 AM (UTC):** 🦸‍♂️ The engineering team, half-asleep, assembled to save the day after the alert system's heroic call.
- **10:10 AM (UTC):** 🕵️‍♂️ Our tech detectives, still rubbing their eyes, suspected a mischievous network issue as the culprit.
- **10:30 AM (UTC):** 🕳️ The rabbit hole of network configuration was explored but turned out to be a red herring.
- **10:45 AM (UTC):** 🚀 The incident got a rocket boost, escalating it to the database and infrastructure teams.
- **11:00 AM (UTC):** 🔍 Database logs spilled the beans - too many connections and queries, a true party overload!
- **11:15 AM (UTC):** 🧘‍♀️ We performed server yoga, adjusting load balancer chakras for a peaceful traffic flow.
- **11:30 AM (UTC):** 🎉 Ta-da! Service was fully restored as our servers finally found their zen.

## `Root Cause and Resolution:`
- **Root Cause:** 😵 Our servers were the life of the party, but unexpected traffic from a marketing campaign led to a server "hangover." Slow response times and errors were their way of saying, "Can't party right now!"
- **Resolution:** 🚦 We made our load balancer the traffic cop, directing requests sensibly. Server connection and query limits were tuned down, letting them catch their breath.

## `Corrective and Preventative Measures:`
1. **Auto-scaling:** 🚀 Our servers will now automatically call for backup when the party gets wild.
2. **Traffic monitoring:** ☕ Our monitoring system will drink extra coffee to stay alert and spot traffic spikes.
3. **Resource limits:** 🛡️ Servers are now trained to say "No" when too many questions are asked - we're teaching them some self-defense.
4. **Failover setup:** 💪 We're setting up a superhero squad of servers for emergency rescues.
5. **Load testing:** 🏋️ Servers are hitting the gym for regular load testing to handle traffic marathons.
6. **Documentation:** 📚 We're writing a thriller novel about incident response procedures, complete with secret agents and suspense.

We apologize for the inconvenience during our servers' unexpected party. Next time, we promise our servers won't invite everyone over without permission. Thank you for your patience, and remember, even servers need a spa day once in a while! 😸🌟


## `Files`

| Filename | Description |
| -------- | ----------- |
| `README.md` | A `README` File |

## `Author:`
### Gideon Selorm Attakpah: <attakpahgideon@gmail.com> - [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
