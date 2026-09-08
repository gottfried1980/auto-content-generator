High Precision Content Generator

Plugin Name: High Precision Content Generator
Version: 15.1
Author: Gottfried Aumann
License: GPL2
Description

The High Precision Content Generator automatically creates highly relevant blog posts using OpenAI's DALL-E 3 for images and YouTube video content. It intelligently generates cohesive, well-structured sentences and selects matching media. You can schedule daily content creation based on WordPress tags, making it a valuable tool for automated content management. Enhanced search algorithms are used to ensure that the generated content is accurate and relevant.
Features

Automatic Content Generation: Generates blog posts with appropriate titles, body text, and media.
OpenAI DALL-E 3 Image Integration: Creates relevant images for blog posts.
YouTube Video Embedding: Automatically searches and embeds relevant YouTube videos.
Scheduled Daily Content: Automatically schedules daily posts based on WordPress tags.
Customizable via Admin Panel: Customize the settings for API keys, content language, and scheduling.
Multiple Languages: Supports English, German, Italian, and French.

Installation

Download the plugin and upload it to your WordPress plugin directory.
Install the necessary dependencies via Composer (vendor/autoload.php).
Activate the plugin in the WordPress admin area.
Configure the plugin settings by navigating to the Content Generator menu.

Usage

Go to Content Generator in the WordPress admin menu.
Set your OpenAI and YouTube API keys.
Define a daily content generation time.
Customize language settings (English, German, Italian, or French).
To generate content manually, enter a topic, select content length, and format, then click Generate.

FAQ
1. Why is content not being generated automatically?

Ensure that you've set a valid daily content generation time in the plugin settings.
Verify that your OpenAI and YouTube API keys are correctly set.

Solution: Go to Content Generator > Settings and check the daily generation time, OpenAI, and YouTube API fields.
2. How do I troubleshoot content not appearing in the posts?

Check if the plugin has successfully created a post by reviewing the admin logs.
Verify that the daily cron event is correctly scheduled.

Solution: Navigate to Content Generator > Settings and check the Last Cron Log section for details on the cron event execution.
3. What happens if the image or YouTube video generation fails?

If a relevant image or video cannot be found, the content will still be generated, but the media may be missing.

Solution: Check your OpenAI and YouTube API rate limits or manually add images/videos to the post.
4. Why is my content generated in the wrong language?

Ensure that you've set the correct language in the plugin settings under Content Generator > Settings.

Solution: Verify that the selected language is correct. The plugin supports English (en), German (de), Italian (it), and French (fr).
Most Likely Errors and Solutions
1. Error: "API key missing"

This error occurs when the OpenAI API key is not set. Solution: Enter a valid OpenAI API key in Content Generator > Settings.

2. Error: "No tags found"

The plugin could not find any tags to generate content. Solution: Ensure your WordPress site has tags and posts tagged appropriately.

3. Error: "HTTP error code 429"

This indicates that you've exceeded the OpenAI or YouTube API rate limit. Solution: Wait until your API rate limit resets, or consider upgrading your API plan.

4. Generated content is incomplete or cut off

This may happen if the API response is too short. Solution: Increase the Content Length setting or try generating the content again.

Changelog

Version 15.1

Removed the display of the "Scheduling Error" message from the admin menu.
Added language-based success messages after content generation directly in the admin interface.
Improved error handling for API key issues and content generation failures.

This plugin provides a seamless way to automate your content creation, allowing you to focus on growing your site while maintaining consistent, relevant posts.