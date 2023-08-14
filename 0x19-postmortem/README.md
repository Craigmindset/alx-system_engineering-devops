Server Outage on July 24th, 2023

We are writing to apologize for the server outage that occurred on July 24th, 2023 at 12:00 PM GMT + 1. This outage resulted in a 37-minute period of downtime for all of our server infrastructure, which prevented our clients from using our services.

The root cause of the outage was the failure to thoroughly verify all implemented upgrades before deploying them to live systems. Specifically, the upgrade that was deployed to our production servers included a requirement for third-party software authentication, but the new implementation was not supported by the current version that is installed on our servers. This caused the servers to crash, resulting in the outage.

We have taken steps to prevent this from happening again. First, we will now push all desired modifications to our test environments before delivering them to a live server. This will allow us to test the changes thoroughly and ensure that they are compatible with our current infrastructure. Second, we will increase the performance metrics threshold to warn on-call engineers of a potential server crash. This will give us more time to react and take corrective action before an outage occurs.

We sincerely apologize for the inconvenience and financial loss that our clients may have incurred during the outage. We are committed to providing our clients with reliable service, and we will continue to work hard to prevent future outages.

Timeline of Events

12:00 PM GMT + 1: Upgrades implementation begins.
12:45 PM GMT + 1: Server outage begins.
1:00 PM GMT + 1: Pagers alert on-call team.
1:10 PM GMT + 1: On-call team acknowledges the outage.
1:15 PM GMT + 1: Rollback initiation begins.
1:20 PM GMT + 1: Successful rollback.
1:22 PM GMT + 1: Server restart initiated.
1:25 PM GMT + 1: 100% of traffic back online.

Thank you for your understanding
