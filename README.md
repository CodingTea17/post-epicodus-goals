# Post-Epicodus Plan (rev 1.0)

##### 12/15/2017

### Summary
Continue to hone my ruby development skills with new projects and continued collaboration. Branch out using online resources to gain experience and knowledge in other languages and frameworks. Attend more meetups to network and learn from the community.

| Actionable Goals  | Priority |
|:---|:---:|
| Utilize D3 and and ActionCable to create a live updating bitcoin price tracking application.  | High |
| Fully complete the Epicodus React course day-by-day.  | High |
| Continue to attend monthly Ruby Brigade meetup as well as the bi-weekly freecodecamp meetups.  | High |
| Attend the Portland Erlang and Elixir User Group monthly meetup: Mini Talks.  | High |
| Continue to explore Elixir and recreate some of my Rails apps using Phoenix. (I have a Udemy course.)  | High |
| Learn how to build an Ethereum Dapp and attend an Ethereum meetup.  | High |
| Complete the Khan Academy course on Cryptography.  | Medium |
| Fully deploy a Rails application to an AWS in production mode.  | Medium |
| Find a React (potentially React/Rails) based open source to contribute to.  | Medium |
| Learn how to make Ruby gems and publish one.  | Medium |
| Create a Rails/React cookbook sharing application.  | Medium |
| Make at least one RoR related post on Linkedin per day.  | Medium |
| Build out a rental management site with features such as remote property management and online rent payment for payments.  | Medium |
| Connect with a fellow Epicodus student at least once a week and pair program for the day.  | Medium |
| Follow up to the one above: Make a cool application that takes people's availability and pairs them for as many days they want per week.  | Low |
| Integrate Firebase(or FireStore) into a rails application.  | Low |
| Reboot the sinatra based foodcart finder application into a Rails project.  | Low |
| Write an in-depth comparison of Angular and React.  | Low |
| Use D3 to make a world heat map of tea and tea exports.  | Low |
| Build an open source API project that tracks smartphone specs since 2007.   | Low |

### What I did Today:
* I created a repo and a README for the 2nd version of the Driver Timer (Nessie).
* I updated the README of the first version of the Driver Timer (Frankenstein).
* I created the project folder for the Driver Timer V3 (Dracula) and setup a rails backend api and a react frontend api.
* I installed ngrok to expose my localhost rails server to the internet which allows me to setup a development webhook for the Nexmo API.
* Setup a project README and a GitHub repo.
* Created a SMS model.
* Constructed an inbound_sms controller to handle incoming messages. Tested it and it works. I sent a message from my phone and the route triggered a pry. Nexmo is currently set to send the message to a GET route because that's how I had it setup for v2 (idk why -\_-) so I will have to go with it for now...
