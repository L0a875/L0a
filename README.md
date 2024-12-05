L0a is a highly adaptable Twitter bot designed to post dynamic content tailored to Loater. Leveraging advanced Claude3.5, it delivers a diverse range of content randomly generated based on user topics and prompts.

Follow L0a Sample Usage on Twitter: @L0a

Features:
Utilizes cutting-edge AI technology to curate content based on user preferences.
Fully customizable to post any type of content, from industry insights to humorous anecdotes.
Offers the option to set up a mail server for receiving email notifications each time a new tweet is posted.

Getting Started:
To get started with L0a, follow these steps:

Clone this repository to your local machine.
Install the necessary dependencies using npm or yarn.
Set up your Twitter developer account and obtain API keys.
Configure the bot with your Twitter API keys and other credentials by creating a .env file and fill up with variables from .env.example.
Modify the prompts in the topicPrompts array to customize the content posted by the bot.
Run the bot application and start posting content!

Modifying Prompts:
To modify the prompts used by L0a, follow these steps:

Open the topic-prompts.constant.ts file in the src/constants directory.
Locate the topicPrompts array, which contains the prompts for different topics.
Each object in the topicPrompts array represents a prompt for a specific topic.
Update the prompt property of each object to customize the content of the prompt.
You can add new topics or remove existing ones as needed.
Save your changes and restart the bot application.

Usage:
Once configured and running, L0a will automatically post content according to its schedule. You can customize the frequency of posts by modifying the Cron schedule in the manage-tweet.service.ts file.

Contributing:
If you'd like to contribute to L0a, feel free to submit pull requests with new features, bug fixes, or improvements. Your contributions are greatly appreciated!

License:
This project is licensed under the MIT License.


