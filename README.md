# AFRICAN CHARITY CHALLENGE

## Purpose and Scope

---

_Installation instructions are found at the end of the document if desired to skip ahead_

This application is a demonstration of a Charity Challenge concept, where an individual or a group are able to contribute to multiple charitable causes in the continent of Africa. While currently detailed with examples only, in its full potential, the application could raise awareness of the work that real life charities are completing all over the continent. While currently at a set 30 individual countries, in full potential the application could be easily adjusted to focus on more or less areas, and could also drive that focus on areas of high concern, with further Research & Development (R&D), using a broad cohort of charities.

Users are able to donate "Charity Coins" which are linked to a real dollar value, towards charitable causes, and these are highlighted on the application map, as they are completed. The application can provide a accessbile mechanism for offering wide-ranging support to many African countries, providing the user with motivation via their map being slowly completed, which, in real-life circumstances, they would be able to share on social media, or work with groups to complete a group challenge.

This type of concept that the application demonstrates is one where the problems of hunger and vulnerability, lack of education, security and sustainable industries, exist in high levels across the continent of Africa. While some of the examples given are one-off charitable causes, such as an immunisation or food pack examples, others focus on support towards longer life supports, such as sustainable fishing or farming, which is an issue to be addressed to allow communities to build their own support structures. The developed application could have a real-world impact if employed in genuine capacity, both on the communities that it supports, and the users who can develop an appreciation of charitable giving.

As previously mentioned, the R&D should not be understated, as there have been examples in the past where support is given that does not address the needs, such as a $10M cashew-processing facility in Tanzania, many years ago, that was designed on the basis of three times the nation's cashew production, meaning that running costs per available cashews were so much higher than plants in India, that it made more sense to export them (1). While this application is designed at a less precise level, deployment in a real-world sense would need to account for sensible solutions that the users are supporting, so they have a genuine impact, and users feel motivated to contribute.

The application is currently designed for a user to select menus that direct them towards either the available charity causes, as indicated on a map, with descriptions as to what the charitable cause entails, or to their "Charity Chest" which is a section for viewing available "Charity Coins" and also with a menu for increasing those "Charity Coins" by using a limited budget, reflective of a bank account balance. Here, users are also able to reach out for group support (sponsorship) or complete "work" so they can increase their budget. Users are able to save their progress on the terminal application, or overwrite it with a new profile.

In the fashion that it is designed, the target audience is, broadly speaking but not exclusive to, those living in wealthier nations or those of wealthier means, who also have ready access to a smartphone or computer. While the terminal application is demonstrable on a larger computer screen, in a real life situation the smartphone would work very well with this concept, where users are also able to upload their progress, with visual displays and comments, to their social media. This would acknowledge that the desire for peer-related feedback can act as a motivation, or could encourage peers to work in groups or embark on their own individual Charity Challenge, all driving towards the purpose to provide additional funding to African communities in need.

1. 2001, Peron, J., Foundation for Economic Education, _The Sorry Record of Foreign Aid in Africa_, viewed 01/10/21, <https://fee.org/articles/the-sorry-record-of-foreign-aid-in-africa/#5>
   > Jennifer Whitaker, How Can Africa Survive? (New York: Harper & Row, 1988), p. 76.

&nbsp;
&nbsp;

## Installation Information

---

### Running the application

The most straightforward way to run the application is to please:

1. download the african_charity_challenge.zip from the github repository <https://github.com/tfxlong/african_charity_challenge/blob/main/african_charity_challenge.zip>
2. unzip the file to a directory of your choice
3. open your directory to the location of the unzipped contents
4. please set terminal window to minium height of 45 rows, and minimum width of 125 columns, to allow the ascii art to run
5. run the file 'run_app.sh'

This executable file will run the program by completing the following steps

1. Check if the gem 'bundle' is installed and, if not, it will install it for you
2. Runs the program via the command 'ruby main.rb'

Alternatively this Ruby gem can be installed manually via a 'bundle install' command from your terminal.

Please note that this program is designed to run with a Ruby environment.

### Dependencies

The following dependencies are required for successful operation of this application:

```Ruby
gem 'json', '~> 2.5'
gem 'rainbow', '~> 3.0'
gem 'tty-cursor', '~> 0.7.1'
gem 'tty-markdown', '~> 0.7.0'
gem 'tty-prompt', '~> 0.23.1'
gem 'tty-screen', '~> 0.8.1'
gem "tty-progressbar", "~> 0.18.2"
```

Due to an integrated Gemfile, there is no manual installation required for these dependencies. The program is designed to install these as part of the running instructions.

_please note that this README.md is for the GitHub repository only_
