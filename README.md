# bot_trap

Trap for bad bots - UliCMS Module

Serios bots and crawlers processes the robots.txt.
The robots.txt is a standard text file format to exclude specific URLs from search engines.
While every serious bot honours the robots.txt file some malicious bots ignore the file.

This module inserts a hidden link to every page.
This link is contained in robots.txt file.
Every serious bot ignores the link because it is listed in robots.txt.
If a bot follows the link it is detected as a bad bot.
bot_trap add it's ip address to a list.
Any future request from this ip are getting blocked.

## Requirements

* UliCMS 2018.3 or later