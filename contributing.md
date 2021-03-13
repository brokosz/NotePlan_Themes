# Contributing
Made something beautiful? Think of a way to improve an existing theme? Here's how to help out.

# How to contribute

Prerequisites:

- Familiarity with [pull requests](https://help.github.com/articles/using-pull-requests) and [issues](https://guides.github.com/features/issues/).
- Knowledge of [Markdown](https://help.github.com/articles/markdown-basics/) for editing `.md` documents.
- Knowledge of [JSON](https://codeblogmoney.com/what-is-json/) and for editing `.json` themes.
- Knowledge of [regex](https://www.sitepoint.com/learn-regex/) for adding and editing custom theme functionality (this is optional). 

In particular, this community seeks the following types of contributions:

- **Themes**: modify an existing theme or add your own to have your work displayed.
- **Ideas**: We're looking for better ways to preview and create themes for people that might not have solid coding abilities but are passionate about customizing NotePlan.
- **Copy editing**: fix typos, clarify functions, and generally improve the quality of the themes.
- **Formatting**: help keep theme content easy to read with consistent formatting.

# Contributing
To add a theme to this repository:

- Create a pull request and add your completed and tested theme to the `bin` folder. If your theme is still a work in progress, please limit your additions to the `src` folder. 
- Create a preview of your theme and add it to the `img` folder. Here's how I create them:
	1. Add the custom theme to NotePlan Theme folder and open `NotePlan > Preferences > Themes`.
	2. Activate your new custom theme. It should have a border around the preview.
	3. Screenshot **just** the active theme preview from the list and open the image in an image editor.
	4. Remove the background and trim the image to the outline of the active border. This can be accomplished in most editing tools by trimming transparent pixels. 
	5. Resize the preview to be `505px` wide and maintain aspect ratio to get the automatic height. 
	6. Name your new preview `<themename>.png` and add to the `img` folder. 
* Update the [readme.md](readme.md) at the root of this repo with the addition of your theme to the preview list. Use the following format:
	```
	## Base Theme Name (not each variant)
	![](/img/themename.png)
	```
	7. Submit your PR with comments on what you added or changed. 
	
# Conduct

We are committed to providing a friendly, safe and welcoming environment for all, regardless of gender, sexual orientation, disability, ethnicity, religion, or similar personal characteristic.

On Discord, please avoid using overtly sexual nicknames or other nicknames that might detract from a friendly, safe and welcoming environment for all.

Please be kind and courteous. There's no need to be mean or rude. Respect that people have differences of opinion and that every design or implementation choice carries a trade-off and numerous costs. There is seldom a right answer, merely an optimal answer given a set of values and circumstances.

Please keep unstructured critique to a minimum. If you have solid ideas you want to experiment with, make a fork and see how it works.

We will exclude you from interaction if you insult, demean or harass anyone. That is not welcome behavior. We interpret the term "harassment" as including the definition in the [Citizen Code of Conduct](http://citizencodeofconduct.org/); if you have any lack of clarity about what might be included in that concept, please read their definition. In particular, we don't tolerate behavior that excludes people in socially marginalized groups.

Private harassment is also unacceptable. No matter who you are, if you feel you have been or are being harassed or made uncomfortable by a community member, please contact the repo owner or any of the NotePlan Discord moderators immediately. Whether you're a regular contributor or a newcomer, we care about making this community a safe place for you and we've got your back.

Likewise any spamming, trolling, flaming, baiting or other attention-stealing behavior is not welcome.

# Communication

GitHub issues are the primary way for communicating about specific proposed changes to this project.

Please follow the conduct guidelines above. Language issues are often contentious and we'd like to keep discussion brief, civil and focused on what we're actually doing, not wandering off into too much imaginary stuff.
