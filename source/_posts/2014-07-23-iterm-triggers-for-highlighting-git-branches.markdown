---
layout: post
title: "Iterm triggers for highlighting git branches"
date: 2014-07-23 14:12:50 +0400
comments: true
categories: [iterm2, osx, git, config]
---
#### The problem
Sometimes it is really hard to determine which commit deployed to your production instance.
Especially, when you have several staging environment and a lot of ongoing feature branches.

#### Solution
Here is a solution provided by iTerm2 triggers:
{% img ../images/img/iterm_trigger_highlighting.png 'git graph in iterm2 with special branches highlighting' %}
See? _haa/master_  highlighted by green background. Much easier to find it.

Also _origin/master_ has different color (purple)

#### Iterm Configuration
It's very easy to configure your iTerm to behave in such way:

1. Open iterm preferences (_Cmd + ,_)
2. Go to Profiles -> Advanced tab
3. Click 'Triggers'
3. Add new "triggers" by clicking "+" button, like following:

{% img ../images/img/iterm_settings.png 'iterm2 trigger settings' %}

That's it!
