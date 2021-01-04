# Welcome to our open Nextcloud hackaton!

> Finally an open hackaton for those speaking Frenglish! 

---

> Enfin un hackaton ouvert pour ceux qui parlent français ! (ou franglais)

## Principles of this open hackaton

Arawa is organizing nearly each week, on Fridays at 14:00 (time of Paris) a hackaton where Arawa employees, partners or any one wanting to learn about the great Nextcloud ecosystem is welcoming to join to hack on a specific Nextcloud topic.

Arawa meaning libre/free in [Hittite](https://en.wikipedia.org/wiki/Hittite_language), we follow an open first company stretegy. Therefore, if you are willing to join us, feel free to [contact us](https://www.arawa.fr/contact)!

Please note that even if our team is fluent in English, these hackatons are organized in French to even reduce further the access barrier to the Nextcloud platform and thus ease the learning curve.

These hackatons are usually taking 2 hours (and longer for whose of you wanting to stay :))

## How to get started for a Nextcloud dev hackaton?

Just make sure you have an instance of Nextcloud installed locally and ready at hand. The best bet to maximize your chances of success is to use an instance freshly installed you are not using for anything else and where no other Nextcloud apps have been installed.

We are not providing a dev environment for this. There is basically no interest in doing so. Providing one would even mean that we risk to step on each other feet when developing. But deploying your dev env locally is also giving you the thrilling experience to learn how to do it, heh! :)

We are however providing a shared folder on our... Nextcloud instance (obviously :p), a repo on our GitHub organization and sharing all our notes with you upon request.

## How is happening an open hackaton in practise?

1. We discuss and publish the schedule of the hackton topic on [our Mattermost channel](https://chat.arawa.fr/) a few days in advance.

   You are not using Mattermost? No issue, we are providing [all the briding tools you need](https://github.com/42wim/matterbridge/) to cross connect your channel to your enterprise chat solution.

2. The D day, we fire our BigBlueButton instance and we are ready to discuss in video, share our screen, takes notes, etc. all using Free and Open Source Software!

   If we have a aquestion nobody has an answer, we write the question on the upstream's Discourse forum ([example](https://help.nextcloud.com/t/x/85511)).

3. At the end of the hackaton session, we take the time to pair review our code, publish our research on our GitHub repo and if the Nextcloud documentation needs corrections, we write a pull request to upstream the changes in the documentation. But if you come up with a personal project, that's okay too.

   Writing documentation takes time to be clear, so if the task is not finished because other Nextcloud contributors are requesting changes, we usually start the next hackaton session by ensuring the upstream process of our documentation changes is happening greatly.

## What technical level should I meet?

These hackatons are not meant to introduce you to the Nextcloud platform is you have never heard about it. If you are in this situation, we can have special one to one demo organized personally to you, [contact us](https://www.arawa.fr/contact/)!

While most of us are developers or people having a technical background, UX / UI experts are welcome to join as well: some sessions are targetting UX / UI. In the past, we even had the Nextcloud UX / UI lead engineer who joined us (yes, we had to switch to English ^^).

On the development side, being confident when speaking about HTTP URL routing and have some experience in database schemas  migrations of PHP apps written with Laravel or CMS like Magento is a substantial advantage and is really helpful to understand Nextcloud internals, but not mandatory. While you could already use tools like Xdebug or Kint to debug your code, if you are not using any of them and prefer the simple `echo` as as log/tracing system, that's fine too (but Nextcloud has [its own](https://docs.nextcloud.com/server/latest/developer_manual//basics/logging.html) mechanisms in place) :)

Join us and happy hacking!