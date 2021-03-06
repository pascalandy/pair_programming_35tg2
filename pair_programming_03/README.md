## Title
This HTML page shall interpret this environment variable set during `docker compose up -d`

## How to quote your price

1. Let's not negotiate, chat or waste anyone's time about this quote. I'm not looking for the cheapest person.
2. If you know what you are doing, you should resolve this **within 10-20 minutes**.
3. I'm welling to pay **20$ US** for this task via upwork.com, hackhands.com or Paypal
4. This request is wide open and the source is available to everyone.

All details here - https://github.com/pascalandy/pair_programming_35tg2/tree/master/pair_programming_03

## Before you start!
- Don't work for nothing! Officially confirm you take charge by **assigning yourself** into the [appropriate issue](https://github.com/pascalandy/pairing-work/issues/).
- If you don't do this, you may work on the same issue as someone else at the same time! I can't pay for this miscommunication. You'll have been warned. :)

## Details about this request

First consider this as a pair programming gig :) I'm using docker-compose v2 with many components like nginx reverse proxy, discovery services (without hard coded IP or Ports), PostgreSQL, Logentries, Load balancer all running remotly into containers. I'm not a newbie and you might as well learn from me :)

***

In docker-compose, you'll see 
env_file:
        - ./ngx-static.env

In `ngx-static.env` I defined: 
FULL_NAME=Pascal&nbsp;Andy

In the HTML this is where the system shall parse the value:
https://github.com/pascalandy/pair_programming_03/blob/master/ngx-static/www/index.html#L33 

It's good to know that the variable `VIRTUAL_HOST=dockercluster.tk` found in the file `ngx-static.env` works and is used by the proxy server.

The goal is to configure this one pager and let none technical people configure it easily.

Can you find a solution?

Cheers!
Pascal

## My expectations

Like you prefer:
A1) Fork this project, and point me to your commits
or ...
A2) Push a PR directly in this repo

B) I test it ... it works :)
C) I pay you :))

## Communications
- **Telegram** is my preferred chat platform.
- Slack is cool. I avoid Skype
- [Twitter](https://twitter.com/_pascalandy)

## References
- (none)

Cheers!
Pascal