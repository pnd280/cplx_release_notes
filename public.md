# Your Perplexity.ai user interface MUST BE in English (en-US). And please turn off any 3rd party translation extenstions/plugins (including browser setttings).

Consider giving a star ⭐ on [Github](https://github.com/pnd280/complexity).

💖 Support the development via [Ko-fi](https://ko-fi.com/pnd280) or [Paypal](https://paypal.me/pnd280).

## v0.0.1.0

_Release date: 24th Aug, 2024_

Complexity is now publicly available on the Chrome Web Store and Mozilla Add-ons.

-   **NEW**: Introducing **Canvas** - an interactive code preview.
-   **NEW**: Paste (very) long text into the query box is now no longer create a file.
-   **NEW**: Drop file to upload within thread.

-   **IMPROVE**: Significantly improved the overall performance (especially long threads).
-   **IMPROVE**: Significantly reduce layout shift while generating new message.

-   **FIX**: Search params will now be respected and work consistently.
-   **FIX**: Fixed various contrast issues (Light + Dark theme).

[Full Issue References](https://discord.com/channels/1245377426331144304/1251725782561193994)

Thanks @Dailyfocus, @brknclck, @paradroid/dayman, @`<Code/>`, @Asura, @Hannah, @somerandomedude, @Lacracotte, @tra1l_blaz3r, @Neon, @moistcornflake, @MyDpi.

## v0.0.0.21 (Hotfix)

_Release date: 1st Aug, 2024_

-   **FIX**: Selectors won't load if payment method is not Stripe.  
    _Why detect subscription status? To disable selectors for free users._

## v0.0.0.20 (Hotfix)

_Release date: 1st Aug, 2024_

-   **FIX**: Adopt new user settings api endpoint.

Special thanks to @sneakyf1shy.

## v0.0.0.19 (Hotfix)

_Release date: 24th July, 2024_

-   **NEW**: Added `Llama 3.1 405B` model option.

## v0.0.0.18 (Hotfix)

_Release date: 30th June, 2024_

-   **FIX**: Fixed a bug where selectors are not showing on the query box (due to Perplexity's html structure change).

## v0.0.0.17

_Release date: 22nd June, 2024_

-   **IMPROVE**: Significantly improve `Tooltips` performance on long threads.
-   **FIX**: Update `Claude 3.5 Sonnet` model name.

## v0.0.0.16

_Release date: 21st June, 2024_

-   **IMPROVE**: Wrap `plain-text` block by default.
-   **FIX**: Sticky thread message toolbar:
    -   Overlaps query input box.
    -   Added **Share** option in shareable thread.
    -   Remove unnecessary buttons in non-editable and non-shareable thread.
-   **FIX**: No contrast on light theme table header color.

Thanks @brknclock1215, @samxiaowastaken.

## v0.0.0.15 (Hotfix)

_Release date: 19th June, 2024_

-   **FIX**: Fixed "Copy without citations" for multi-steps Pro search answers.

Thanks @sifu.

## v0.0.0.14 (Hotfix)

_Release date: 19th June, 2024_

-   **FIX**: Fixed a bug where unable to set default text/image model.
-   **FIX**: Fixed redirection to changelog page.

Thanks @Redactado.

## v0.0.0.13

Release date: _18th June 2024_

-   **NEW**: Block Perplexity's telemetry.
-   **IMPROVE**: Reduced layout shift when open a floating element (Removed all focus guards).
-   **IMPROVE**: Slightly improved performance in long threads.
-   **FIX**: Fixed infinite Cloudflare loop check.
-   **FIX**: Thread query format switch now correctly shown on the toolbar. Notice that the switch will not be shown for query that have no markdown formatting.
-   **FIX**: Fixed a bug where Pro search UI briefly flashes when it's already turned off.
-   **FIX**: Fixed a bug where "Collapse empty thread's visual columns" doesn't consistently work.
-   **FIX**: Removed css injections from API pages.
-   **FIX**: Removed unintended "zeros" at the bottom of the home page.

Thanks @MyDpi, @Redactado.

## v0.0.0.12

Release date: _16th June 2024_

-   **NEW** | **EXPERIMENTAL**: Sticky thread message toolbar. "**Thread Query Markdown**" is now merged with this setting.
    ![Sticky thread message toolbar](https://i.imgur.com/WRD4ISa.png)
-   **NEW**: Auto refresh the page on Cloudflare session timeout.
-   **NEW**: Improved programming experience:
    -   Added code block toolbar to markdown query.
    -   Apply theme (VSCode Dark) to native blocks to ensure consistency with the Diff Viewer.
    -   Supports syntax highlighting for unsupported languages on Perplexity (CSharp, Blade).
    -   Declutter code block toolbar - hide options when not needed.
        ![Code block toolbar](https://i.imgur.com/SlgQ1MU.png)
-   **IMPROVE**: Diff Viewer now supports syntax highlighting for:
    -   Java, HTML, CSS, XML, CLike, Bash, C, Cpp, Gradle, GraphQL, JSON, Makefile, Markdown, PowerShell, Rust, Sass, SCSS, SQL, Kotlin, Haskell, PHP, Apex, Blade.
-   **IMPROVE**: Improved update notifications.
-   **FIX**: Unintentionally inject scripts into Perplexity's subdomains.
-   **FIX**: Fixed a bug where only empty visual column of the first message query is collapsed (PPLX's html structure changed).
-   **CHANGES**:
    -   **Removed** message auto scroll: already implemented on Perplexity.

Thanks @Redactado (github: [@Reddishye](https://github.com/Reddishye)) for the `blade` prism plugin.

## v0.0.0.11

Release date: _10th June 2024_

-   **NEW**: Introducing **Diff Viewer** - compare text/code changes side by side. For text, just ask the AI to wrap any text with triple backticks (\`\`\`).
    ![Diff Viewer](https://i.imgur.com/wr6kTtW.png)

-   **FIX**: Enhanced code block toolbar randomly crashes.
-   **FIX**: Fixed a bug where toggle the AI profile in the collection selector will break other functionalities.
-   **FIX**: Fixed a bug where Export button doesn't work.
-   **FIX**: Corrected AI Profile character limit (1000 -> 1500).
-   **IMPROVE**: Dark theme: Enhanced text contrast.

## v0.0.0.9

Release date: _9th June 2024_

-   **NEW**: Auto scroll to the bottom of the thread when new messages are being generated, scroll up for any amount to abort. (currently not support existing/editing/rewriting messages)
-   **NEW**: Export thread without sources/citations.
-   **NEW**: Improved code block with a sticky toolbar with options to copy, wrap, show line numbers, and collapse/expand the block.
-   **IMPROVE**: Query box selectors bar prematurely wrap on small width viewport.
-   **FIX**: Light theme: selected text in some places has no indicator.
-   **FIX**: Collection selector - current selected item not being default selected when open.
-   **FIX**: Incorrect thread message query format switch labels.

Thanks @`<Code/>`, @trai1_blaz3r, @StinkWhistle.

## v0.0.0.8

Release date: _6th June 2024_

-   **NEW**: Export all messages in a thread (including sources).
    -   Pages and publicly shared threads by others are **NOT** yet supported.
-   **NEW**: Collection selector will now have a "Default" option that is directly linked to your AI Profile.
-   **NEW**: Improved personalization:
    -   Custom Slogan/Heading/Trademark or whatever you want to call it.
    -   Custom UI font & Monospace font.
    -   Custom Accent color.
-   **NEW**: Toggle message queries between plain text and markdown format (The switch is on the top-right corner of each message query).
-   **IMPROVE**: Overall performance has been improved.
-   **FIX**: Fixed minor UI glitches/inconsistencies.

Thanks @paradroid/dayman, @Toxon, @`<Code/>`.

## v0.0.0.7

Release date: _4th June 2024_

-   **FIX**: Pro search toggle `Ctrl + i` hotkey doesn't work.
-   **FIX**: Inconsistent color in Pages.
-   **FIX**: Inconsistent Tooltip fonts.

## v0.0.0.6

Release date: _2nd June 2024_

-   **NEW**: Added an inline menu to quickly invoke models/collections/web access focus.
-   **IMPROVE**: Disabled unusable features if the user doesn't have an active Perplexity subscription.
-   **IMPROVE**: Warns the user about incompatible interface language.
-   **FIX**: Fixed a bug where web focus doesn't persist if the Pro switch is on.
-   **FIX**: Fixed minor UI bugs and inconsistencies.

## v0.0.0.4

-   **NEW**: Added Collection Selector:
    -   Quickly initiate new chat with a collection without hard-navigating to the collection page.
    -   View and Edit collection details.
-   **NEW**: Custom CSS injection (Extension Options => Custom Theme).
-   **NEW**: Render message query in markdown format (+ Double-click to edit).
-   **IMPROVE**: Automatically collapse empty thread's visual columns.

## v0.0.0.2

-   **NEW**: Added Thread table of contents: navigate through long threads with ease

## v0.0.0.1

-   Initial release
