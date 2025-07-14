# Word list  

**Note**: This document includes references to terms that Google considers
disrespectful or offensive. The terms are listed here to provide usage
guidance and alternative terms.

This word list covers style and usage guidelines that are specific to developer documentation.

If the term that you're looking for isn't on this list, check our other
[editorial resources](/style#editorial-resources), including our preferred
dictionary,
[Merriam-Webster](https://www.merriam-webster.com/). If there are multiple spellings in
the Merriam-Webster word entry, use the first form listed, which is the most common spelling. For
example, in the
[entry for *cancel*](https://www.merriam-webster.com/dictionary/canceled),
the first form listed for the past tense is *canceled*, indicating that it's more common than
*cancelled*.

If you're looking for a technical definition, then it's often a good idea to check the
authoritative documentation on the topic.

Terminology decisions, including how and when to define or contextualize
terms, often require judgments based on factors like your product area,
your audience, and prevailing convention. Here are some other pages of this
guide that can help you make those types of judgments:

* [Jargon](/style/jargon)
* [Inclusive language](/style/inclusive-documentation)
* [Write for a global audience](/style/translation)
* [Hyphens](/style/hyphens)
* [Capitalization](/style/capitalization)

As always, it's fine to deviate from our guidance if that serves your readers
better.

## Word list

All word list entries have a link link
icon next to them. To link directly to an entry, you can right-click and
copy the link address, or click and copy the URL from your address bar.

Some word list entries include guidance to *avoid* or *don't use* a
term. Apply this guidance as follows:

### Numbers and Symbols

+
:   OK to use *+* with numbers in text, such as *customer records with
    300+ demographic attributes*, except in formal contexts.

& (ampersand)
:   Don't use *&* instead of *and* in headings, text, navigation, or
    tables of contents.
:   It's OK to use *&* when referencing UI elements that use *&*, or
    in table headings and diagram labels where space constraints require
    abbreviation.
:   It's OK to use `&` for technical purposes in code.

### A

a and an
:   Use *a* when the next word starts with a consonant *sound*,
    regardless of what letter it starts with.

A/B testing
:   Capitalize and use slash notation for *A/B*.

abnormal
:   Don't use to refer to a person.
:   OK to use to refer to a condition of a computer system.

abort
:   Avoid in general usage. Instead, use words like *stop*, *exit*,
    *cancel*, or *end*. In Linux, *abort* refers to a type of
    signal that terminates an abnormal process.

about versus on
:   When a cross-reference includes information that describes what the
    cross-reference links to, use *about* instead of *on*.

above
:   Don't use for a range of version numbers. Instead, use
    [*later*](#later).
:   Don't use to refer to a position in a document. Instead, use
    *earlier* or *preceding*.
:   Don't use to refer to a position in the UI. Instead, write instructions
    that avoid directional language.
:   It's OK to use *above* in a non-directional way, such as when describing a hierarchy.

access (verb)
:   Avoid when you can. Instead, use friendlier words like *see*,
    *edit*, *find*, *use*, or *view*.

access token
:   Lowercase except at the beginning of a sentence,
    heading, or list item.

account name
:   Don't use. Instead, use [*username*](#username).

actionable
:   Avoid unless it's the clearest and simplest phrasing for your audience.
    Instead, leave it out or replace it with a phrase like *that you can act
    on* or *useful*.
:   Don't use *actionable* in the legal sense without consulting a
    lawyer.

action bar
:   In Android documentation, don't use. Instead, use
    [*app bar*](#app-bar).

ad tech
:   Write out on first mention: *advertising technology (ad tech)*.
:   Don't use *adtech* or *ad-tech*.

address bar
:   Use to refer to the URL bar or the combined URL bar and search box in a
    browser.
:   Don't use *omnibox*.

ad hoc
:   OK to use in database and analytics contexts to mean "free-form" or
    "user-written" (for example, *ad hoc queries* or *an ad hoc
    chart*). For other contexts, try to find a more specific English
    equivalent.
:   Don't hyphenate or italicize the term.

admin
:   Write out *administrator* unless it's the name of a UI label or other
    element.
:   It's OK to use *admin* in Android
    documentation.

administrator
:   In Android documentation, don't use. Instead, use *admin*.

advertised route priority
:   OK to also use *base advertised route priority* when discussing
    region-to-region costs.
:   Don't shorten or use variations of these terms.

agnostic
:   Don't use. Instead, use a more precise term like
    *platform-independent*.

AI
:   In general, you can use *AI* without spelling out *artificial intelligence*.
:   Most readers are familiar with the abbreviation *AI*. If you think your audience isn't
    familiar with the term, spell it out on first use.

aka
:   Don't use. Instead, write out *also known as*, or present an
    alternative term using parentheses or the word *or*. You can also
    write out a definition.
:   Recommended:
    Geographic data, also known as geospatial data, is ...
:   Recommended: Geographic data
    (geospatial data) is ...
:   Recommended: Geographic data, or
    geospatial data, is ...

all apps screen
:   In Android documentation: Lowercase except at the beginning of a sentence,
    heading, or list item.

allowlist (verb), allowlisted, allowlisting
:   Don't use as a verb. Instead, rewrite to improve clarity.
:   OK to use *allowlist* as a noun.
:  

allows you to
:   Don't use. Instead, use *lets you*.

alpha
:   Lowercase except when part of a product name.
:   Recommended: PRODUCT\_NAME
    Alpha
:   Recommended: PRODUCT\_NAME
    is in alpha.

America, American
:   Use only to refer to the *Americas* or the *American continent*.
:   Don't use to refer to the United States. Instead, use a more precise term
    like *the US* or *the United States*, and *people in the
    US*.

among

AM, PM
:   To be consistent with [Material Design](https://material.io/design/communication/data-formats.html#date-and-time),
    use all caps, no periods, and a space before.
:   Recommended: 9:00 AM
:   Recommended: 10:30 PM

and/or
:   Don't use unless space is limited, such as in a table.

Android
:   When referring to the operating system, capitalize *Android*.

Android-powered device
:   Not *Android device*.

and so on
:   Avoid using *and so on* whenever possible.

anti-pattern
:   Avoid using *anti-pattern*, particularly as a standalone heading.
    Instead, consider using a more specific and broadly understood term.
:   Recommended: Avoid these five SQL
    errors.
:   Recommended: Avoid these five
    programming practices that make SQL queries inefficient.
:   Not recommended: Avoid these five SQL
    anti-patterns.

API
:   Use *API* to refer to either a web API or a language-specific API.
:   Don't use *API* when referring to a method or a class. For example,
    don't write *This resource has one API* to mean "This resource has
    one method."

API key
:   Not *developer key* or *dev key*.

APIs Explorer
:   Not *API explorer* or other variants.

app
:   In general, use *app* instead of *application* when referring to
    programs for end users, especially in the context of mobile or web
    software.
:   In some contexts, such as enterprise software, it's OK to use
    *application* to convey a sense of greater complexity.
:   Use *application* in standard phrases such as *application
    programming interface*.

app bar
:   In Android contexts, formerly *action bar*.

appendix
:   Use the plural *appendixes*, not *appendices*.

application

as
:   If you mean *because*, then use *because* instead of
    *as*. *As* is ambiguous; it can refer to the passage of time.
    *Because* refers to causation or the reason for something.

as of this writing
:   Avoid because this phrase is implied. The phrase can also prematurely
    disclose product or feature strategy or inappropriately imply that a
    product or feature might change.

:   Recommended: BigQuery doesn't support
    that function.
:   Not recommended: As of this writing,
    BigQuery doesn't support that function.

authentication and authorization
:   In general, use the word *authenticated* only to refer to users,
    and use *authorized* only to refer to requests that are sent by a
    client app on behalf of an authenticated user.

    A user *authenticates* their identity by entering their password
    (or giving some other proof of identity). The *authenticated
    user* then *authorizes* the client app to send an
    *authorized request* to the server on the user's behalf.
:   When you want to use a preposition with *authenticate*, use
    *against*.

authN, authZ
:   Don't use. Instead, use *authentication* or *authorization*.

autohealing
:   Not *auto-healing*.

auto mode VPC network
:   Not *auto mode network*.

autopopulate
:   Not *auto populate* or *auto-populate*.

autoscaling
:   Not *auto-scaling*.

autotagging
:   Not *auto-tagging*.

autoupdate
:   Don't use. Instead, use *automatically update*.

-aware
:   Avoid using as a compound modifier, as in *healthcare-aware*.
:   OK to use when it's part of a product name, such as *Identity-Aware
    Proxy*.

### B

backend
:   Not *back-end* or *back end*.

bar
:   Avoid when possible.

bare metal
:   Lowercase except at the beginning of a sentence,
    heading, or list item.
:   Hyphenate when used as a compound modifier, such as *bare-metal
    server*.

base64
:   Lowercase except at the beginning of a sentence,
    heading, or list item. Otherwise, capitalize *Base64* only if it's part of a
    formal name.
:   Write *base64* in code font *only* if it's a string literal or
    otherwise quoted from code.

baz
:   Avoid when possible.

below
:   Don't use for a range of version numbers. Instead, use
    [*earlier*](#earlier).
:   Don't use to refer to a position in a document. Instead, use *later*
    or *following*.
:   Don't use to refer to a position in the UI. Instead, write instructions
    that avoid directional language.
:   It's OK to use *below* in set phrases such as *below (the)
    average*, *below the mean*, *below zero*.
:   It's OK to use *below* in a non-directional way, such as when describing a hierarchy.

best effort
:   Avoid where possible. Instead, use more specific wording. After providing
    a description, you can add a phrase like "sometimes referred to as *best
    effort*."

beta
:   Lowercase except when part of a product name.
:   Recommended: PRODUCT\_NAME
    Beta
:   Recommended: PRODUCT\_NAME
    is currently in beta.

between versus among
:   It's fine to use *between* when talking about more than two things;
    however, *between* isn't interchangeable with *among*.
:   Use *between* when you're talking about two or more distinct
    things:
:   Recommended: JavaScript introduces
    dependencies between the DOM, the CSSOM, and JavaScript execution.
:   Use *among* when you're talking about things that are part of a group
    or things that aren't distinct:
:   Recommended: ... a conventional SQL
    database that can be shared among multiple apps.
:   More examples:
:   Recommended: Because screen
    dimensions vary widely among devices (for example, between phones and
    tablets, and even among different phones), you should configure the
    viewport so that your pages render correctly on many different devices.
:   Not recommended: Because screen
    dimensions vary widely between devices (for example, between phones and
    tablets, and even between different phones), you should configure the
    viewport so that your pages render correctly on many different devices.
:   Recommended: You can share services
    among multiple clients.
:   Not recommended: You can share
    services between multiple clients.
:   See also [Grammar Girl's
    discussion of *between* and *among*](http://www.quickanddirtytips.com/education/grammar/between-versus-among).

big-endian
:   Hyphenate. Lowercase except at the beginning of a sentence,
    heading, or list item.
:   Recommended: The codebase assumes
    big-endian byte ordering.
:   Not recommended: The codebase assumes
    Big Endian byte ordering.
:   Not recommended: The codebase assumes
    Big-endian byte ordering.
:   Not recommended: The codebase assumes big
    endian byte ordering.

billing charges
:   Don't use *billing charges* to mean charges that appear on a bill.
    Instead, use *billed charges*.
:   Use *billing charges* to describe the cost of creating the bill.

black-box
:   Avoid using *black-box*, *blackbox*, or *black box* to
    describe monitoring and testing. Consider using a more precise term for
    clarity.

    * For monitoring, use *synthetic monitoring*.
    * For testing, use *opaque-box testing*.

Black Friday
:   Avoid unless explicitly referring to an event in the US. Instead use
    *peak scale event*.

blackhat, black hat, black-hat
:   Don't use. Instead, use precise terms for the kind of violation or
    practice, such as *illegal*, *unethical*, or *in violation of
    rules*.

blackhole (verb), blackholed (adjective)
:   Don't use. Instead, use a more descriptive term or phrase, such as
    *dropped without notification*.

blacklist, black list, black-list
:   Don't use *blacklist*, *whitelist*, and *graylist*.
    Instead, use more precise terms that are appropriate for your domain.
:   * For the noun *blacklist*, consider using a replacement such as
      *denylist*, *excludelist*, or *blocklist*.
    * For the noun *whitelist*, consider using a replacement such as
      *allowlist*, *trustlist*, or *safelist*.
    * For the noun *graylist* (*greylist*), consider using a
      replacement such as *provisional list*.
:   In all of these cases, consider that there might not actually be a list
    involved. When replacing problematic terms, be sure to be technically
    accurate for the specific context.
:   For the verb forms of these words, a simple word-for-word replacement
    typically isn't the best solution. Instead, replace verbs such as
    *blacklisted* with phrases that accurately convey the relevant
    action. For example:
:   Recommended: To deny requests from
    an IP address, add it to the `dos.yaml` file.
:   Not recommended: To denylist an IP
    address, add it to the `dos.yaml` file.
:   Don't use: To blacklist an IP
    address, add it to the `dos.yaml` file.
:   If the command or code that you're documenting uses one of these words,
    then use the words only in direct reference to the code items
    ([formatted as code](/style/code-in-text)), and make it clear
    what you're referring to.
:   Recommended: Add a user to the
    allowlist (`whitelist`) by entering the following:
    `whitelist adduser EMAIL_ADDRESS`.
:   Not recommended: Add a user to the
    whitelist by entering the following: `whitelist adduser
    EMAIL_ADDRESS`.

blacklisted, black listed, black-listed
:   Don't use.

blacklisting, black listing, black-listing
:   Don't use.

blast radius
:   Don't use. Instead, use a more precise term like *affected area* or
    *spatial impact*.

blind
:   Avoid using *blind to* or *blind eye to*. Instead, use more
    precise terms like *ignore*, *unaware of*, *disregard*,
    *avoid*, or *reject*.
:   Avoid using *blind writes*. Instead, use a more precise phrase, such
    as *a write operation without a read operation*.
:   Avoid using *blind change* or *change blindly*. Instead, use a
    more precise phrase such as *change without first confirming the
    value*.
:   When referring to people, use terms like *person who is blind*,
    *screen reader user* (if applicable), *person who is visually
    impaired*, *person who is low-vision*, *magnification user*
    (if applicable).

blue-green
:   Not *blue/green* or *blue green*.

boolean
:   In most contexts, *boolean* refers to a specific data type in a
    specific programming language. In such cases, use code font and the exact
    spelling and capitalization of the programming keyword.
:   When referring to the abstract data type, use lowercase.
:   If you refer to *Boolean mathematics* or *Boolean logic*, use
    uppercase.

brown bag, brown-bag
:   Don't use. Instead, use a more precise term like *learning session*,
    *lunch and learn*, *lunchtime learning session*,
    *casual training*, or *informal training*.

build cop, build sheriff
:   Don't use. Instead, use a more precise term like *build monitor*.

button
:   In a UI, a link isn't the same as a button; don't use the term
    *button* to refer to a link.
:   Use *button* to refer to mechanical buttons (like the volume control
    buttons on the side of a phone) and capacitive touch buttons on a phone
    (like the Home button). You *press* mechanical buttons, and
    *tap* capacitive and on-screen buttons.

### C

can
:   Use *can* in the following ways:

    * To convey permission or ability (for example, "You can access the
      server").
    * To refer to an optional action (for example, "You can also view
      logs with the Log Viewer").
    * To describe a possible outcome (for example, "The process can
      take 30 minutes").
:   See also [could](#could), [may](#may),
    [might](#might), [must](#must),
    [should](#should), and [would](#would).
:   For information about clarifying who's performing an action, see
    [Active voice](/style/voice).

canary
:   Don't use *canary* as a verb, and don't use *canarying*.
:   When possible, avoid [jargon](/style/jargon) like *canary* and
    *canary testing*. If you use one of these phrases, define it on first
    use or provide a link to the definition, and use it consistently
    throughout the document.

cell phone, cellphone
:   Don't use. Instead, use *mobile phone*, or if you're talking about
    more than phones, then use *mobile device*.
:   It's OK to use *phone* (without *mobile*) when the context is
    clear.:   cellular data
        :   Don't use. Instead, use *mobile data*.

        cellular network
        :   Don't use. Instead, use *mobile network*.

        chapter
        :   When referring to documentation that isn't in the form of a book, don't
            use the term *chapter*. Instead, refer to documents, pages, or
            sections.

        check
        :   Don't use to refer to marking a checkbox. Instead, use *select*.
        :   Recommended: Select **Automatically
            check for updates**.
        :   Not recommended: Check **Automatically
            check for updates**.

        checkbox
        :   Not *check box*.

        choose
        :   *Choose* is fine to use for generic contexts. For UI elements, use
            [select](#select).

        chubby
        :   Don't use. Instead, use a word that clearly explains what you mean, such
            as *unused* or *overextended*.

        clear
        :   Use (as a verb) to refer to clearing a check mark from a checkbox.
        :   Recommended: Clear **Automatically
            check for updates**.
        :   Not recommended: Uncheck
            **Automatically check for updates**.
        :   Not recommended: Deselect
            **Automatically check for updates**.

        CLI
        :   Don't use *CLI* generically to refer to a command-line interface.
            Instead, refer to the specific command-line interface, such as the
            [Google Cloud CLI](#gcloud).

        click
        :   When the environment is a desktop with a mouse, use *click* for most
            targets, such as buttons, links, list items, and radio buttons. Don't use
            *click on*.
        :   Recommended: Click **OK**.
        :   Not recommended: Click on **OK**.
        :   Hyphenate *right-click*, *left-click*, and *double-click*.
        :   When a click or tap action reveals a collapsed list, you can write
            *click to expand* or simply *expand*.
        :   It's OK to write *click in* when referring to a region that needs
            focus (for example: *click in the window*), but not when referring to
            a control or a link.
        :   For Android apps, don't use
            *click*. Instead, use [tap](/style/word-list#tap).

        click here
        :   Don't use. For information and alternatives, see
            [Avoid vague link text](/style/cross-references#vague-link-text).

        clickthrough (noun), click through (verb)

        client
        :   In REST and RPC API documentation, *client* is short for *client
            app*—that is, the app that the developer is writing.
        :   Don't use *client* as an abbreviation for *client library*;
            instead, use *library*.

        client ID
        :   Lowercase except at the beginning of a sentence,
            heading, or list item.

        client secret
        :   Lowercase except at the beginning of a sentence,
            heading, or list item.

        codebase
        :   Not *code base*.

        cold
        :   When possible, avoid [jargon](/style/jargon) like *cold
            failover*, *cold standby*, and *cold spare*. If you use one
            of these phrases, define it on first use and use it consistently
            throughout the document.

        colocate
        :   Not *co-locate* or *colo*.

        compliant, compliance
        :   Use with caution. A claim that a product or its output is *compliant*
            with a standard is a strong statement.

        comprise
        :   Don't use. Instead, use *consist of*, *contain*, or
            *include*.

        config
        :   Avoid when possible. Instead, spell out the full word when it's used in a
            non-code sense: *configuration* or *configuring*. Use the
            verbatim code item name when referring to, for example, a data structure
            or a file with that name.

        confidential
        :   *Confidential* data is data that is protected to prevent unauthorized access. See
            [sensitive](#sensitive).

        cons
        :   Don't use. Instead, use a more precise term, such as *disadvantages*.

        console
        :   Use *the* before the name of a console.
        :   To refer to a sub-page of a console, use the term *page*.
        :   If a specific term for a browser-based interface is unavailable, use
            *web interface*.

        content type
        :   Be as specific as possible when writing about a content type, and use the term only when applicable.
            For example, you can use this term if you're referring to the value of the `Content-Type` HTTP header.
           

        Control+S, Command+S, and other keyboard commands
        :   To refer to a `Control` character, use
            `Control`+CHARACTER.
        :   Don't use *Ctl-S*, *Cmd-S*, or *Cloverleaf-S*.
        :   In most cases, use an uppercase letter for CHARACTER.
        :   In macOS, many keyboard commands use the `Command` key instead of
            the `Control` key, and there's an `Option` key instead
            of an `Alt` key. If your audience includes macOS users and
            Windows or Linux users, then mention both keyboard commands.
        :   Recommended: `Control+S`
            (`Command+S` on macOS)

        Copy and paste
        :   Avoid using. Instead, explain what to enter into a field and not how.
        :   Recommended: In the
            **Query** field, enter the output from the previous step.
        :   Not recommended: Copy the output from
            the previous step and paste into the **Query** field.

        could
        :   Avoid using. Instead, use *can* where possible.
        :   See also [can](#can), [may](#may),
            [might](#might), [must](#must),
            [should](#should) and [would](#would).
        :   For information about clarifying who's performing an action, see
            [Active voice](/style/voice).
        :   For information about tenses, see [Present
            tense](/style/tense).

        CPU
        :   All caps. No need to expand the abbreviation on first mention.

        crazy, bonkers, mad, lunatic, insane, loony
        :   Don't use. Instead, use *complicated*, *complex*,
            *baffling*, *strange*, or *unexpected*, and only for
            inanimate objects.

        Create a new ...
        :   Avoid using unless you need to distinguish the item from another recently
            created item. Instead, use *Create a ...*
        :   Recommended: Create a project.
        :   Not recommended: Create a new project.

        cripple
        :   Don't use. Instead, use more precise language. For example, instead of
            *it crippled the server*, write *it slowed the server down*.
        :   When referring to people, use terms that specifically describe a physical
            impairment, such as *person with a motor disability*; *person with
            a mobility impairment* (refers to walking or moving about); *person
            with dexterity impairment* (refers to using a standard mouse or
            keyboard); *person who uses a wheelchair, walker, or cane*;
            *wheelchair user*; *person with restricted or limited mobility*.

        cross-site request forgery
        :   Lowercase except at the beginning of a sentence,
            heading, or list item.

        curated roles
        :   Don't use. Instead, use *predefined roles*.

        currently
        :   Avoid because this word is implied. The word can also prematurely disclose
            product or feature strategy or inappropriately imply that a product or
            feature might change.
        :   See also
            [as of this writing](#as-of-this-writing) and
            [presently](#presently).
        :   Recommended: Windows isn't supported.
        :   Not recommended: Windows isn't
            currently supported.

        custom mode VPC network
        :   Not *custom mode network*.

        curl
        :   Not *cURL*.

        Cyber Monday
        :   Avoid unless explicitly referring to an event in the US. Instead use
            *peak scale event*.

### D

dash
:   A dash (`—`) isn't the same character as a hyphen
    (`-`). The characters are used for different purposes.
    Therefore, don't use the word *dash* to refer to a hyphen.

data
:   Use *data* as singular, not plural; *the data is*, not
    *the data are*.
:   Use data as a mass noun, not a count noun; *less data*, not
    *fewer data*.

data center
:   Not *datacenter*.

data center campus
:   Use when referring to an entire physical location, which can encompass one
    or more data centers.

data cleaning
:   Not *data cleansing*.

data flow (noun); dataflow (noun)
:   If it's possible to replace with the phrase *flow of data*, then use
    two words: *data flow*.
:   If that replacement doesn't work, such as when referring to something like
    stream processing or reactive programming, then use one word:
    *dataflow*.

data source
:   Not *datasource*.

datastore
:   Not *data store*.

data type
:   Not *datatype*.

dead-letter queue, dead letter
:   Define on first use, for example *dead-letter queue (unprocessed
    messages queue)*.

deep linking
:   Not *deep-linking*. However, if you can replace with
    *linking*, then do so.

deficient
:   Don't use to refer to a person.
:   OK to use to refer to a condition of a computer system.

deformed
:   Don't use to refer to a person.
:   OK to use to refer to a condition of a computer system or
    inanimate object.

demilitarized zone (DMZ)
:   Don't use. Instead, use a more precise term like *perimeter network*.

denigrate
:   Don't use. Instead, use *disparage*.

denylist (verb), denylisted, denylisting
:   Don't use as a verb. Instead, rewrite to improve clarity.
:   OK to use *denylist* as a noun.
:  

deprecate
:   To *deprecate* an item is to recommend against the item's use,
    typically as a warning that the item will soon be unavailable or
    unsupported. Don't use *deprecated* to mean *removed*,
    *deleted*, *shut down*, or *turned down*.

deselect
:   Don't use to refer to clearing a check mark from a checkbox. Instead, use
    *clear*.
:   Recommended: Clear **Automatically
    check for updates**.
:   Not recommended: Deselect
    **Automatically check for updates**.
:   Not recommended: Uncheck
    **Automatically check for updates**.

desire, desired
:   Don't use. Instead, use a word like *want* or *need*.
:   Recommended: Set the value to the
    size that you want.
:   Not recommended: Set the value to
    the size that you desire.
:   Not recommended: Set the value to
    the desired size.

Developers Console
:   Don't use.

DevOps
:   Short for *development operations*. No need to spell out on first
    mention unless the audience requires it.

dialog
:   Use *dialog* for the UI element sometimes called a [dialog box](http://wikipedia.org/wiki/Dialog_box).
:   Use *dialogue* only for verbal interaction between people.

directory, folder
:   If the context that you're documenting (such as an IDE's GUI) uses one
    term or the other, use that term. If not, then use *directory* in a
    command-line context, and *folder* in a GUI context. When in doubt,
    default to *directory*.

disable
:   Don't use *disable* or *disabled* to describe something that's
    broken.
:   When describing a user action or the state of a UI element, use a more
    precise term where possible. You can use *inactive*,
    *unavailable*, *deactivate*, *turn off*, or
    *deselect*, depending on the context. Use the same term consistently throughout your
    document.
   

disclosure triangle, disclosure widget
:   Don't use. Instead, use *expander arrow*.

display (verb)
:   Don't use as an intransitive verb. *Display* is a transitive verb;
    therefore, it requires an object. It is often misused in technical
    documentation, as demonstrated by the following example:
:   Recommended: The Output Directories
    area appears.
:   Recommended: The Output Directories
    area is displayed.
:   Not recommended: The Output
    Directories area displays.
:   The following example demonstrates correct usage of the verb
    *display* but means something quite different from the preceding
    examples.
:   Recommended: The Output Directories
    area displays the vector image.

distributed denial-of-service (DDoS)
:   Hyphenate as shown. On subsequent mention, use *DDoS*.

DNS server policy
:   Lowercase *server policy*.

DNSKEY
:   One word, all capital letters.

documentation or document or documents
:   To refer specifically to the text on a page that explains a product, feature, or service,
    use *this document*, and not *this article*, *this topic*, *this doc*, or
    *this page*. It's OK to use *this tutorial*, *this quickstart*, or *this
    codelab* for those specific documentation types.

    Always spell out *documentation* except in cases where space is limited, such as in
    tabs and URLs.

    See also
    [page](#page).
:   Recommended: You can find many
    examples in this document.
:   Not recommended: You can find many
    examples in this article.
:   Recommended: This document provides
    guidance about creating tables.
:   Not recommended: This page provides
    guidance about creating tables.

documentation set
:   Not *doc set* or *docset*.

does not yet
:   Avoid in timeless documentation because this phrase can become outdated.
    The phrase can also prematurely disclose product or feature strategy or
    inappropriately imply that a product or feature might change.
:   Recommended: The Google Cloud console
    doesn't support this IAM role.
:   Not recommended: The Google Cloud
    console does not yet support this IAM role.

dojo
:   Don't use. Instead, use a precise term that is accurate for the context,
    such as *training* or *workshop*.

domain name registrar
:   Lowercase except at the beginning of a sentence,
    heading, or list item.

Domain Name System Security Extensions (DNSSEC)
:   Write out and capitalize each word on first use. OK to abbreviate as
    *DNSSEC* after first use.

double-tap
:   Hyphenate. Lowercase except at the beginning of a sentence,
    heading, or list item.

downscope
:   Consider using a more descriptive term like *constrain scope* or
    *reduce scope*. Because *downscope* might not be broadly
    understood, if you use the term, make sure to define it on first use.:   :   Don't use *down scope* or *down-scope*
        :   Recommended: Reducing the scope of a
            token helps you follow the principle of least privilege.
        :   Recommended (first use): The IAM
            recommender helps you *downscope* (reduce) the permissions that are
            available to your users.

        drag
        :   Use *drag*, not *click and drag* and not *drag and drop*.
        :   OK to use *drag-and-drop* as an adjective.
        :   Recommended: Drag the USER
            to the **Authorized** box.

        drop-down
        :   In most cases, you can omit *drop-down* from phrases like *drop-down list* or
            *drop-down menu*, and just use *list* or *menu*. Include *drop-down* as a
            modifier only if the omission would cause ambiguity. Don't use *drop-down* as a
            standalone noun.

        dumb down
        :   Don't use. Instead, use a word or phrase what's happening, such as
            *simplify* or *remove technical jargon*.

        dummy variable
        :   Don't use to refer to placeholders. Instead, use *placeholder*.
        :   Also don't use if referring to the concept in statistics known as a
            [dummy variable](https://en.wikipedia.org/wiki/Dummy_variable_(statistics)).
            Instead, use alternate terms such as
            *indicator variable*, *design variable*, *one-hot
            encoding*, *Boolean indicator*, *binary variable*, or
            *qualitative variable*.

### E

each
:   *Each* refers to every individual item taken individually, not to a
    group of items taken collectively. In other words, *each* isn't a
    synonym for *all*. For example, *a list of each item* is
    ambiguous; *a list of all the items* or *a list of the items* is
    generally clearer.

earlier
:   Use for a range of version numbers, not *lower*.
:   Recommended: Use version 2.2 or
    earlier.
:   Not recommended: Use version 2.2 or
    lower.
:   In Android documentation, don't use
    *earlier* for a range of version numbers. Instead, use *lower*.
:   When referring to a position in a document, use *earlier* or
    *preceding*, not *higher*.

easy, easily
:   What might be easy for you might not be easy for others. Try eliminating
    this word from the sentence because usually the same meaning can be conveyed
    without it.

ecommerce
:   Not *e-commerce*.

edge availability domain
:   Don't use *edge availability zone*, *metro availability domain*,
    or *metro availability zone*. Don't shorten to *EAD*.

e.g.
:   Don't use. Instead, use phrases like *for example* or *such as*.
    Many people confuse *e.g.* and *i.e.*

egress
:   When referring to the networking term, use lowercase.

either
:   When using *either*, use parallel syntax.
:   Recommended: Do either option 1 or
    option 2.
:   Recommended: Either do option 1 or
    do option 2.
:   Not recommended: Either do option 1
    or option 2.
:   In general, use *either* only for a choice between two things, not
    for a choice among multiple things. Writing *either A or B or C* will
    distract some readers, but if it's the best phrasing for your situation,
    then use it.

element
:   In HTML and XML, a tag is a component of an element that indicates
    the start or end of the element. (For example, the
    `<i>` start tag indicates the beginning of the
    `<i>example</i>` element.) In general, don't use
    the term *tag* to refer to an entire element.

email
:   Not *e-mail*, *Email*, or *E-mail*.
:   Don't use as a verb.
:   Use a specific verb in front of the word. For example, *send email*.
    This construction is better for translation and a
    [global audience](/style/translation).

emoji
:   Use *emoji* for both singular and plural forms. See [Don't
    know the difference between emoji and emoticons? Let me explain](https://www.theguardian.com/technology/2015/feb/06/difference-between-emoji-and-emoticons-explained) and [What's the Plural of Emoji?](http://www.theatlantic.com/technology/archive/2016/01/whats-the-plural-of-emoji-emojis/422763/)

enable
:   In procedures, use the appropriate label and action for the
    [UI element](/style/ui-elements) that the user interacts with. When describing a
    user action or the state of a UI element, use a more precise term where possible. It's OK to
    use *enable* when not referring to a person.
:   For turning on or activating an option or feature, use *enable* or
    *[turn on](#turn-on)* consistently:

    * Use the same term in introductory text as described in the
      procedure.
    * Use the same term throughout the document unless there's a
      difference in the UI elements for different procedures.
:   Recommended: To enable the API,
    click the toggle.
:   Recommended: Enable the API for your
    project.
:   For making it feasible to do something, use *lets you*.
:   Recommended: The API lets you detect
    features in images.
:   Not recommended: The API enables you
    to detect features in images.
:   Not recommended: The API allows you
    to detect features in images.

endpoint
:   Not *end point*.

enter
:   Use *enter* to refer to the user entering text. If it's important to
    not press `Enter`, explicitly say so. See also
    [*type*](#type).
:   Recommended: In the **Owner** box,
    enter your name.
:   Recommended: In the **Size** box,
    type a font size.

ephemeral external IP address
:   Don't use *ephemeral IP address* or *external IP address* to
    refer to ephemeral external IP addresses.

error-prone (adjective)
:   Hyphenate. Lowercase except at the beginning of a sentence,
    heading, or list item.

etc.
:   Avoid using *etc.*, *and so forth*, and *and so on*
    wherever possible. If you really need to use one, use *etc.*
    Always include the period, even if a comma follows immediately after.
:   Recommended: Your app might experience
    problems such as instability or high latency.
:   Recommended: Your app might experience
    problems, including instability or high latency.
:   Not recommended: Your app might
    experience instability, high latency, and so on.
:   Not recommended: Your app might
    experience instability, high latency, etc.
:   Not recommended: If your app
    experiences instability, high latency, etc., follow these steps:

eventually
:   Avoid in timeless documentation because this word can become outdated. The
    word can also prematurely disclose product or feature strategy or
    inappropriately imply that a product or feature might change.
:   See also
    [future](#future) and [soon](#soon).
:   Recommended: This version of the SDK
    is deprecated.
:   Not recommended: This version of the
    SDK is deprecated and eventually will be no longer supported.

execute
:   Verb commonly used to refer to function calls, SQL queries, and other processes. When the meaning
    is the same, use the simpler word *run* instead. If you need to use a more precise term
    for your context, use that term.

expander arrow
:   The UI element used to expand or collapse a section of navigation or
    content. If you describe this element, use the terms *expander arrow*
    and *expandable section*
:   Don't use terms like *expando* or *zippy*.

exploit
:   Don't use *exploit* to mean "use."
:   Only use *exploit* in the negative sense, such as to describe
    *exploiting a security vulnerability*.

external VPN gateway
:   Write *external* and *gateway* all lowercase except at the
    beginning of a sentence, heading or list item.

extract
:   Use instead of *unarchive* or *uncompress*.

### F

fail over (verb), failover (noun, adjective)

fat
:   Don't use. Instead, use a precise modifier that conveys the appropriate
    meaning. For example, use *high-capacity network connection* instead
    of *fat connection* or *full-featured client* instead of *fat
    client*.
:   Instead of using fat in a negative sense, such as *trim the fat*,
    refer in a more concrete manner to the *removal of unused items*.
:   OK to use as an acronym when referring to file allocation table (FAT).

female adapter
:   Don't use. Instead, use a genderless word like *socket*.

Fast Healthcare Interoperability Resources (FHIR)
:   Refer to *a FHIR* (pronounced "a fire," as in "a FHIR store"), not *an FHIR*.

filename
:   Not *file name*

file system
:   Not *filesystem*.

fill in; fill out
:   Use *fill in* when referring to entering information in individual
    fields.
:   Use *fill out* when referring to completing an entire form.:   :   Recommended: Fill out the
            questionnaire. Be sure to fill in the required fields.

        final solution
        :   Don't use. Instead, use *solution* as a standalone term or, depending
            on the context, *definitive*, *optimal*, *best*, or *last
            solution*.

        fintech
        :   Write out on first mention: *financial technology (fintech)*. Don't
            use *FinTech* or *fin-tech*.

        firewalls
        :   Don't use in Compute Engine or networking documentation. Instead, use
            *firewall rules*.
        :   Exception: If you're explaining how firewall rules work, you can explain
            that every network has an implied virtual distributed firewall.
        :   Outside of Compute Engine or networking documentation, the term
            *firewalls* is acceptable.

        first-class, first-class citizen, first class
        :   Don't use socially-charged terms for technical concepts where possible.
            Instead, consider terms such as *core feature*, *built-in*,
            *top-level*.

        following
        :   It's not necessary to use a noun after *following* unless it helps
            provide clarity and enables accessibility.
        :   Recommended: ... in the following
            code sample ...
        :   Recommended: ... in the following
            table ...
        :   Recommended: ... do the following:
            ...

        foo
        :   Avoid when possible even though it's a common term in the developer
            community. Instead, use a clearer and more meaningful placeholder name.

        for instance
        :   Avoid when possible. Instead, use *for example* or *such as*.

        frontend
        :   Not *front-end* or *front end*.

        functionality
        :   Use with caution. With respect to hardware or software,
            *functionality* refers to a set of associated functions or
            capabilities and how they work. However, the word is sometimes overused,
            especially when the intended meaning is *capabilities* or
            *features*.

        future, in the future
        :   Avoid in timeless documentation because this word or phrase can become
            outdated.

### G

GBps
:   Short for *gigabytes per second*. By convention, we don't use
    *GB/s*.

Gbps
:   Short for *gigabits per second*. By convention, we don't use
    *Gb/s*.

gender-neutral he, him, or his (or she or her)
:   Don't use. Instead, use the singular *they* (see [Jane Austen and other famous authors violate what everyone learned in
    their English class](http://www.pemberley.com/janeinfo/austheir.html)). Don't use *he/she* or *(s)he* or other
    such punctuational approaches.

generative AI
:   Spell out *generative*. Use sentence case.
:   Don't use *gen AI* or *Gen AI*.
:   Don't hyphenate *generative AI* as an adjective unless you must do
    so for clarity.

grandfather clause, grand-father clause, grand father clause
:   Don't use.

grandfathered
:   Don't use to refer to something that is allowed to violate a rule because
    it predates the rule. Instead, use an adjective like *legacy* or
    *exempt* or a verb like *made an exception*.
:   Recommended: The app is exempt because
    it was released before the new requirements were announced.
:   Not recommended: The app is
    grandfathered in because it was released before the new requirements were
    announced.

gray-box, grey-box
:   Avoid using *gray-box*, *graybox*, or *gray box* to
    describe testing.
:   To refer to testing that's a combination of clear and opaque testing
    methods, describe exactly what it's doing.
:   If you need to refer to this type of testing after you describe it,
    consider using a more precise term for clarity, such as *translucent-box
    testing*.

grayed-out, greyed-out, gray out, grey out
:   Don't use. Instead, use *unavailable*.

grayhat, greyhat, gray hat, grey hat
:   Don't use. Follow the guidance for [black hat](#blackhat) when
    referring to someone violating rules or laws.

graylist, greylist, gray list, grey list, gray-list, grey-list
:   Don't use.

graylisted, greylisted, gray listed, grey listed, gray-listed, grey-listed
:   Don't use.

graylisting, greylisting, gray listing, grey listing, gray-listing, grey-listing
:   Don't use.

guru
:   If possible, use a more precise term. For example, if you mean
    *expert* or *teacher*, use those terms.

guys, you guys
:   When referring to a group of people use non-gendered language, such as
    *everyone* or *folks*.

gypsy
:   Don't use. To refer to the people, use *Romani*, *Roma*, or
    *Traveller*, as appropriate for the specific group you're referring
    to. In place of metaphorical uses of the term, use more precise phrases.

### H

hamburger, hamburger menu
:   Don't use. Instead use the `aria-label` for that particular
    icon. For example, menu **Menu**.

hands off, hands-off
:   Use a less figurative phrase, such as *automated*. If you're
    referring to a group that doesn't do anything during a process, write a
    description.

hands on, hands-on
:   Use a less figurative phrase, such as *customizable*, or write a
    description of the activity.

hang, hung
:   Don't use to refer to a computer or system that is not responding.
    Instead, use *stop responding* or *not responding*.

happiness and satisfaction
:   Use *happiness* when referring to a customer's perception of a
    site's reliability. Use *satisfaction* when referring to whether the
    site meets the customer's needs.
:   Site reliability engineering (SRE) content generally refers to
    measuring *customer happiness* instead of *customer
    satisfaction*. The two phrases are not equivalent.
:   The distinction the SRE documentation makes is between satisfying a need
    (a dispassionate act) and establishing an emotional response (creating
    happiness). Although it is difficult to measure happiness precisely, SRE
    uses [service level indicators
    (SLIs)](#service-level-indicator) to quantify user perception. For example, a customer might feel
    a "need" to watch a show on TV. If the show is available, the customer's
    need is satisfied. But if playback is slow or choppy, the customer might
    not be happy.

hardcode (verb), hardcoded (adjective)

he, him, his
:   Don't use a gendered pronoun except for a specific individual of known
    gender. Use *they* and *their* for the general singular pronoun.

healthcare
:   Not *health care* or *health-care*.

health check
:   Use with caution. When describing an action taken for a computer system,
    only use the term *health check* if this is the term that appears in
    the interface. Be certain to remove any ambiguity regarding whether the
    term refers to health in the medical sense.
:   Use detailed, non-figurative language as much as possible, such as
    referring to a node *being responsive* instead of referring to a node
    being healthy.

healthy
:   Don't use.

high availability (noun), high-availability (adjective)
:   Lowercase except when part of a product name, but OK to abbreviate as
    *HA* after first use.

higher
:   Don't use for a range of version numbers. Instead, use [*later*](#later).
:   Don't use to refer to a position in a document. Use *earlier* or
    *preceding*.
:   Don't use to refer to a position in the UI. Instead, write instructions
    that avoid directional language.
:   In Android documentation, use
    *higher* for a range of version numbers, not *later*.
:   A release with the highest version number might not be the latest version.
    For example, if version 2.0 of an operating system receives a bug-fix
    update after version 3.0 has been released, then version 2.0.1 might be
    the latest version, even though its version number is lower than 3.0.

high performance computing (HPC)
:   Don't hyphenate. Lowercase except at the beginning of a sentence,
    heading, or list item.

hit
:   Don't use as a synonym for *click*, *press*, or *type*.

hold the pointer over
:   Only use this verb phrase in the following cases:

    * When the user needs to hold their mouse over a UI element, but not
      click the UI element. This action involves waiting for the UI to
      react—for example, waiting for a tooltip to open or waiting for a
      submenu to open.
    * When the duration of time is important.

    The phrase *point to* is more common.

:   Recommended: In the **Admin**
    menu, hold the pointer over **File**, and then click **New**.
:   Not recommended: In the **Admin**
    menu, hover over **File**, and then click **New**.

holiday, the holidays
:   Don't use to refer to the end of the year. Instead, refer to specific
    quarters or months.

home screen
:   Two words in Android contexts; not *homescreen* or
    *home-screen*.

hostname
:   Not *host name*.

hot
:   When possible, avoid [jargon](/style/jargon) like *hot failover*,
    *hot standby*, and *hot spare*. If you use one of these phrases,
    define it on first use and use it consistently throughout the document. However, see
    [hotspot](#hotspot).

hotspot[link](#hotspot)
:   In databases, *hotspots* occur when a small number of nearby rows are
    accessed frequently in a short period of time, causing CPU spikes and
    affecting performance. Use *hotspot* and *hotspots* as nouns.
    Don't use verb and gerund forms such as *hotspotting*, because they
    translate less consistently.
:   When you use *hotspot*, define it the first time that you use it on
    a page as you normally do with jargon.
:   Recommended: Hotspots in one table
    can affect the performance of other tables.
:   Not recommended: Hotspotting in one
    table can affect the performance of other tables.

housekeeping, house keeping, house-keeping
:   Don't use. Instead, use less figurative and more precise terms, such as
    *maintenance* and *cleanup*.

hover
:   Don't use. Instead use [*hold the
    pointer over*](#hold-the-pointer-over).

HTTPS
:   Not *HTTPs*.

### I

IaaS
:   Write out on first mention: *infrastructure as a service (IaaS)*.

ID
:   Not *Id* or *id,* except in string literals or enums.
:   In some contexts, it's best to spell out as *identifier* or
    *identification*.

i.e.
:   Don't use. Instead, use phrases like *that is*. Many people confuse
    *e.g.* and *i.e.*

if
:   Although it is common in casual usage to omit the word *then* in *if...then*
    statements, you should include helper words like *then* in technical documentation. For
    more information, see
    [Use clear, precise, and unambiguous language](/style/translation#clear-language).

image
:   *Image* by itself doesn't localize well because of its many meanings. Consider adding
    context—for example, *disk image* or *container image*.

impact
:   Use only as a noun. Instead of writing that something *has an
    impact*, use the word *affect*.
:   Recommended: This issue affects
    user experience.
:   Acceptable: This issue has an impact
    on user experience.
:   Not recommended: This issue impacts
    user experience.

index
:   Use the plural *indexes* unless there is a domain-specific reason
    (for example, a mathematical or financial context) to use *indices*.

ingest
:   Use *import*, *load*, or *copy* when referring to simple movement of data. Use
    *ingest* only when referring to such operations that also involve significant processing
    of the data.

ingress
:   When referring to the networking term, use lowercase. When referring
    to the GKE term or API, capitalize *Ingress*.

in order to
:   Avoid *in order to*; instead, use *to*.
:   Use *in order to* when needed to clarify meaning or to make
    something easier to read.
:   Recommended: You can use
    monitoring to help identify issues.
:   Not recommended: You can use
    monitoring in order to help identify issues.
:   Recommended: The infrastructure is
    required in order to support search.
:   Not recommended: The infrastructure
    is required to support search.

inline
:   One word as an adjective, *inline*, not *in line* or
    *in-line*.

instance group
:   Don't abbreviate to *IG*. See also [managed instance
    group](#mig).

intercluster
:   Use unhyphenated *intercluster*, not *inter-cluster*.

interconnectAttachment
:   Use when referring to the API. Otherwise, use [*VLAN attachment*](#vlan).

Interconnect connection
:   Only use *Interconnect connection* relative to a product as follows:

    * CDN Interconnect connection
    * Cloud Interconnect connection
    * Dedicated Interconnect connection
    * Partner Interconnect connection

    OK to use *connection* on subsequent mentions.
:   When you're referring to a Google Cloud product, always specify the
    product name. Don't use *Interconnect* or *interconnect* as
    standalone terms, and don't use generic terms like *cloud interconnect
    connection* or *cross-connect*.

Interconnect connection location
:   Only refer to an *Interconnect connection location* in context of a
    specific product, for example *CDN Interconnect*.
:   OK to also use *colocation facility*.

interconnect type
:   Don't use. Instead, use *connection type*. Examples of connection
    types are a *dedicated connection* or a *connection provided by a
    service provider*.

interface
:   OK to use as a noun.
:   Don't use as a verb. Instead, use *interact*, *talk*,
    *speak*, *communicate*, or other similar terms.

internal DNS
:   Write *internal* all lowercase except at the beginning of a
    sentence, heading, or list item.

Internationalized Domain Name (IDN)
:   Write out and capitalize each word on first use. OK to abbreviate as
    *IDN* after first use.

internet
:   Lowercase except at the beginning of a sentence,
    heading, or list item.

Internet Key Exchange (IKE)
:   Write out and capitalize each word on first use. OK to abbreviate
    *IKE* after first use.

I/O (see also [Google I/O](#google-io))
:   Not *I-O* or *IO*.

IoT
:   OK to use as an abbreviation for *Internet of Things*. Note
    the lowercase *o*.

IPsec
:   Not *IPSec* or *IPSECShort*.
:   Short for *Internet Protocol Security*. No need to spell out on
    first mention.

### J

jank, janky
:   Use only to refer to a glitch or problem with graphics that is caused by a loss of data or
    inadequate refresh rate. Don't use otherwise. Use a less figurative term to refer to something
    of poor or unreliable quality.

just
:   Avoid. Usually, *just* is a filler word that you can delete without
    affecting your meaning.
:   Recommended: BigQuery skips the row.
:   Not recommended: BigQuery just skips
    the row.
:   If your meaning is unclear without *just*, then use a more specific
    term such as *only*, *instead*, or *previously*, or revise
    your language to be more specific. (Even if one of these replacement
    terms fits, you often don't need it.)
:   Recommended: You can run DML
    statements in the same way that you'd run a `SELECT`
    statement.
:   Not recommended: You can run DML
    statements just as you'd run a `SELECT` statement.
:   Recommended: Let a user query only
    the table without full dataset access.
:   Recommended: Let a user query the
    table without full dataset access.
:   Not recommended: Let a user query
    just the table without full dataset access.
:   Sometimes, *just* is useful for conveying that one approach is
    simpler than another. In those cases, use *just* instead of
    [*simply*](#simple).
:   Recommended: Use the namespace ID
    `namespace:example-kind` or just `example-kind`.

### K

k8s
:   Don't use. Instead, use *Kubernetes*.

KBps
:   Short for *kilobytes per second*. By convention, we don't use
    *KB/s*.

Kbps
:   Short for *kilobits per second*. By convention, we don't use
    *Kb/s*.

kebab, kabob, kebab menu, kabob menu
:   Don't use. Instead use the `aria-label` for that particular
    icon. For example, more\_vert
    **More**.

kebab case, kabob case, kebab-case, kabob-case
:   Don't use. Instead, use *dash-case*.

key
:   Don't use as an adjective in the sense of *crucial* or
    *important*.
:   If you use *key* as a noun, specify which kind of key you're
    referring to on first mention, because there are many kinds of
    keys in technical contexts.

key pair
:   A pair of keys, such as a public key and a private key. Contrast with
    *key-value pair*, which refers to a pairing that specifies a value
    for a variable (as in configuration files).

key ring
:   Use instead of *keyring* (without the space) when referring to a
    grouping of Cloud KMS keys.

key-value pair
:   Use instead of *key/value pair* or *key value pair*.

kill
:   Avoid when possible. Instead, use words like *stop*, *exit*,
    *cancel*, or *end*. For exceptions to this rule, see
    [Documenting command-line
    syntax](/style/code-syntax#linux-signals).

### L

lame
:   Don't use. Instead, use precise, non-figurative language to refer to a
    deficiency in a component.

later
:   Use for a range of version numbers, not *higher*.
:   Recommended: Use version 2.2 or
    later.
:   Not recommended: Use version 2.2 or
    higher.
:   Not recommended: Use version 2.2+.
:   A release with the highest version number might not be the latest version.
    For example, if version 2.0 of an operating system receives a bug-fix
    update after version 3.0 has been released, then version 2.0.1 might be
    the latest version, even though its version number is lower than 3.0.
:   In Android documentation, don't use
    *later* for a range of version numbers. Instead, use *higher*.
:   When referring to a position in a document, use *later* or
    *following*, not *below*.

latest
:   Avoid in timeless documentation because this word can become outdated.
:   If you must use *latest*, give the reader a reference
    point—for example, a version number or release date.
:   Recommended: To help keep your
    system secure, install the latest version of the tools.
:   Recommended: The June 2021 release
    includes the latest tools that help secure your system.
:   Not recommended: The product includes
    the latest tools that help secure your system.

learnings
:   Don't use. Instead, refer to *knowledge* or *things that you
    learned*.

left-nav, right-nav
:   Don't use directional language.
:   If referring to applications, use *[navigation menu](/style/ui-elements#term-navigation-menu)*.
:   If referring to navigational elements for documentation, use *content
    navigation menu*.

legacy
:   If possible, use a more precise term. If you do use *legacy*,
    include or point to a definition to clarify what you mean in the current
    context. Don't use *legacy* with any sort of pejorative
    connotation.

let's (as a contraction of *let us*)
:   Don't use if at all possible.
:   Not recommended: Let's click the
    **OK** button now.

Letter of Authorization and Connecting Facility Assignment (LOA-CFA)
:   Write out and capitalize each word on first use. OK to abbreviate as
    *LOA-CFA* after first use.

leverage
:   Avoid using if you mean *use*. If possible, use a more precise term.
    For example, *use*, *build on*, or *take advantage of*.

lifecycle
:   Not *life cycle* or *life-cycle*.

lift and shift

    like versus such as
    :   It's OK to use either *like* or *such as* for comparisons or
        examples.

    limits
    :   In an API context, *limit* often refers to usage limits (number of
        queries allowed per second or per day). Where possible, specify the kind
        of limit that you mean, such as *usage limit* or *service
        limit*; the word *limit* can refer to many different kinds of
        limits, including rules about acceptable use.

    lint
    :   Write both command-line tool name and command in lowercase. Use code font
        except where inappropriate.

    little-endian
    :   Hyphenate. Lowercase except at the beginning of a sentence,
        heading, or list item.
    :   Recommended: The codebase assumes
        little-endian byte ordering.
    :   Not recommended: The codebase assumes
        Little Endian byte ordering.
    :   Not recommended: The codebase assumes
        Little-endian byte ordering.
    :   Not recommended: The codebase assumes
        little endian byte ordering.

    livestream
    :   Not *live stream*.

    load balancing (noun), load-balancing (adjective)

    lock screen
    :   Two words in Android contexts; not *lockscreen* or
        *lock-screen*.

    login (noun or adjective), log in (verb)
    :   For the verb form, *sign in* is generally better.
    :   If you're documenting a tool that uses the term *log in*, then use
        that term.

    long press
    :   In Android documentation, don't use. Instead, use *touch & hold*.
        (Not *touch and hold*.)

    long-running operation
    :   Not *long running operation*.
    :   OK to abbreviate as *LRO* after the first use.

    lower
    :   Don't use for a range of version numbers. Instead, use [*earlier*](#earlier).
    :   Don't use to refer to a position in a document. Instead, use *later*
        or *following*.
    :   Don't use to refer to a position in the UI. Instead, write instructions
        that avoid directional language.
    :   In Android documentation, use
        *lower* for a range of version numbers, not *earlier*.

### M

male adapter
:   Don't use. Instead, use a genderless word like *plug*.

man hours, manhours, man-hours
:   Avoid using gendered terms. Instead use terms like *person hours*.

man-in-the-middle (MITM)
:   Avoid using gendered terms. Instead use terms like *on-path
    attacker* or *person-in-the-middle (PITM)*.

manmade, man made
:   Avoid using gendered terms. Instead use a word like *artificial*,
    *manufactured*, or *synthetic*.

manned
:   Avoid using gendered terms. Instead use terms like *staffed* or
    *crewed*.

manpower, man power, man-power
:   Avoid using gendered terms. Instead use terms like *staff* or
    *workforce*.

Markdown
:   Always capitalized, even when you're referring to a nonstandard version.

master
:   Use with caution. Never use in conjunction with *slave*. Where
    possible, replace *master* with a specific term that is accurate for
    the context, such as *primary*, *main*, *original*,
    *parent*, *initiator*, *driver*, *controller*,
    *manager*, *mixer*, *aggregator*, *publisher*,
    *leader*, or *active*.

    Guidance | Recommended | Not recommended || Don't use *master* in conjunction with *slave* in any context. | Cloud SQL primary/replica | Cloud SQL master/slave |
    | Avoid using *master* where possible. | * GKE control plane * Jenkins controller * root key (in security) * primary key (in databases) | * GKE master plane * Jenkins master * master key (in security) * master key (in databases) |
:   If the command or code that you're documenting uses the literal word
    *master*, then use this word only in direct reference to the code
    item ([formatted as code](/style/code-in-text)), make it clear
    what you're referring to, and use the new term thereafter.

Material Design
:   Capitalize each word in *Material Design*.

matrix
:   Use the plural *matrixes* unless there is a domain-specific reason
    (for example, a mathematical context) to use *matrices*.

may
:   In general, reserve for official policy or legal considerations.
:   To convey *possibility*, use *can* or *might*
    instead.
:   To convey *permission*, use *can* instead.
:   See also [can](#can), [could](#could),
    [might](#might), [must](#must),
    [should](#should), and [would](#would).
:   For information about clarifying who's performing an action, see
    [Active voice](/style/voice).

MBps
:   Short for *megabytes per second*. By convention, we don't use
    *MB/s*.

Mbps
:   Short for *megabits per second*. By convention, we don't use
    *Mb/s*.

media type
:   In general, use the term [*media type*](https://www.iana.org/assignments/media-types/media-types.xhtml).
    In contexts where you need to refer to a *content type*—For example, if you mention
    the `Content-Type` HTTP header—it's okay to use *content type* instead, to avoid
    confusion. Don't use *MIME type*.

meta\*

metafeed
:   Not *meta-feed*.

metageneration
:   Not *meta-generation*.

method
:   In programming contexts where *method* refers to a member of a class
    (as in Java), avoid also using the word generically to mean "approach" or
    "manner."

metropolitan area (metro)
:   In networking, a *metro* is a city where a colocation facility is
    located.

microservices
:   Not *Microservices* or *micro-services*.

might
:   Use to convey possibility or an uncertain outcome (for example, "You
    might be prompted to enter your credentials").
:   See also [can](#can), [could](#could),
    [may](#may), [must](#must),
    [should](#should), and [would](#would).
:   For information about clarifying who's performing an action, see
    [Active voice](/style/voice).

MIME type
:   *MIME* stands for "Multipurpose Internet Mail Extensions," and was originally used to
    refer to email standards.
    Don't use *MIME* when you mean [*media type*](https://www.iana.org/assignments/media-types/media-types.xhtml).
    If you feel that might be ambiguous to an audience familiar with the term *MIME*,
    then you can write *media (MIME) type* for clarity.

mobile
:   Don't use *mobile* as a standalone noun. Instead, specify
    *mobile phone*, or if you're talking about more than phones, then use
    *mobile device*.

mobile data
:   Use instead of *cellular data*.

mobile device
:   Use *mobile device* when you're referring to more than phones (for
    example, tablets and phones). It's OK to use *phone* (without
    *mobile*) when the context is clear.

mobile network
:   Use instead of *cellular network*.

mobile phone
:   If you're talking about more than phones, then use *mobile device*.
    It's OK to use *phone* (without *mobile*) when the context is
    clear.

mom test
:   Don't use *mom test*, *grandmother test*, *grandma test*,
    or *girlfriend test*. Instead, use terms like *beginner user
    test* or *novice user test*.

monkey, monkey test
:   Don't use *monkey* to refer to people. When referring to tests, refer
    to the specific function. For example: *automated, random tests*.

multi\*

multi-cluster
:   Hyphenate. We generally prefer to close prefixed words, but this is an
    exception because it's an established term.

multi-region, multi-regional
:   You can use *multi-regional* as an adjective in the context of
    multi-regions, but consider *multi-region* as
    an attributive noun instead, such as in "The dataset is in the EU
    multi-region location." Use *multiregional* in other contexts.

multi-service
:   Hyphenate. We generally prefer to close prefixed words, but this is
    an exception because it's an established term.

multi-tenancy
:   Hyphenate. We generally prefer to close prefixed words, but this is
    an exception because it's an established term.

must
:   Use to describe a required action or state (for example, "You must have
    the Editor role"). You can also write *you need* in order to convey a
    requirement.
:   See also [can](#can), [could](#could),
    [may](#may), [might](#might),
    [should](#should), and [would](#would).
:   For information about clarifying who's performing an action, see
    [Active voice](/style/voice).

### N

N/A
:   Not *NA*. Spell out as *not available* or *not applicable*
    on first reference.

name server
:   Not *nameserver*.

namespace
:   Not *name space*.

native
:   Avoid using *native* to refer to people.
:   When referring to software products, try to use a more precise
    term—for example, use *built-in* to describe a feature that's
    part of a product.
:   The term *native* isn't necessarily clear—for example,
    *cloud-native* could mean that something was written for the cloud,
    or that it's built in to a cloud platform, or that it currently exists in
    a cloud platform.
:   Alternatives to a term like *cloud-native* could include:
    *modern cloud*, *born in the cloud*, *cloud first*, and
    *cloud-born*.

navigation bar
:   Don't use to refer to a *navigation menu*.

neither
:   Write *neither A nor B*, not *neither A or B*.

network IP address
:   Don't use. Instead, use *internal IP address*.

new, newer
:   Avoid in timeless documentation because this word can become outdated.
:   *New* also implies that the reader knows the older product and that
    labeling something as *new* is therefore meaningful.
:   If you must use *new*, give the reader a reference point—for
    example, a version number or release date.
:   Don't use *newer* to refer to a specific version of a product.
    Instead, use [*later*](#later). Make sure that you provide
    a version number or release date by which to understand *later*.

    In Android documentation, use
    [*higher*](#higher) instead of *later*.
:   Recommended: The service's network
    analysis feature reports on network health.
:   Not recommended: Network analysis, a
    new feature in the service, reports on network health.

ninja
:   Don't use to refer to a person. Instead, use a term such as *expert*.
    OK to use in reference to companies, tools, software packages, and other
    entities that use the term in their names.

non\*

nonce
:   Use with caution: this term has a secondary slang meaning that can cause
    confusion for global readers. Always define the term on first use, and
    only use it in specific technical contexts such as authentication and
    blockchain.
:   In end-user documentation and other contexts, use a more descriptive
    phrase, such as *a number that will be used only once*.

non-key
:   An exception to our usual preference for closed forms.

NoOps
:   Don't use. Instead, use *fully managed*. If you must include the
    term, define it at first use with language such as *fully managed* or
    *no operations*, but not *non-operational*. Don't use
    *noops*.
:   For an instruction that does nothing, use
    [*no-op*](https://wikipedia.org/wiki/NOP_(code)) or the
    specific instruction name for your context.

NoSQL
:   Not *No-SQL* or *No SQL*.

notification drawer
:   In Android contexts, don't hyphenate. Lowercase except at the beginning of a sentence,
    heading, or list item.

now
:   Avoid when describing features of products or services because this word
    is implied.
:   If the intent of the text is a comparison between past and present, you
    can use *now*—for example, "In versions of the tool earlier
    than 1.10, you could use only the default value, but now you can assign a
    custom value."
:   Recommended: This feature lets you use
    combinations of user properties.
:   Not recommended: This feature now lets
    you use combinations of user properties.

nuke
:   Don't use. Instead use *remove* or *attack*. For example, a
    *denial-of-service attack*.

### O

OAuth 2.0
:   Not *OAuth 2*, *OAuth2*, or *Oauth*.

off-the-shelf, commercial off-the-shelf (COTS)
:   Use more widely understood terms like *ready-made*, *prebuilt*,
    *standard*, or *default*.

old, older
:   Don't use to refer to a previous version of a product. Instead, use
    [*earlier*](#earlier).
:   Make sure that you provide a version number by which to understand
    *earlier*.
:   In Android documentation, use
    [*lower*](#lower) instead of *earlier*.
:   Recommended: This functionality
    doesn't work in versions earlier than 1.17.0.
:   Not recommended: This functionality
    doesn't work in older versions.

omnibox
:   Don't use. Instead, use *address bar*.

once
:   If you mean *after*, then use *after* instead of *once*.

on-premises
:   Not *on prem*, *on premise*, or *on-premise*. Hyphenate
    when used as any part of speech.
:   Use to refer to a customer's resources that they manage in their own
    facilities. Don't use *peer*.
:   It can be acceptable to use *on-premises* as a noun when it would be
    awkward to repeatedly write out a full phrase like *an on-premises
    environment*. However, it's preferable to use the more complete phrase
    whenever possible.
:   Recommended: An on-premises database.
:   Recommended: The database runs
    on-premises.
:   OK: Moving data from on-premises to
    Google Cloud.

OS
:   OK to use as a shortening of "operating system."

outpost
:   Don't use. Instead, use *channel*.
:   Recommended: social media channels

outside the box, out of the box, out-of-the-box
:   Avoid using in a figurative way. OK to use literally.

overview screen
:   In Android documentation, don't use. Instead, use *recents screen*.

### P

PaaS
:   Write out on first mention: *platform as a service (PaaS)*.

page
:   Use *page* to refer to the following:

    * A whole web page, which can include text, images, links, banners, navigational panes,
      and other features.
    * A sub-page of a [console](#console) in particular.

    See also
    [documentation or document or documents](#documentation).
:   Recommended: To refresh the page, press `F5`.

parameter
:   In our API documentation, *parameter* is usually short for *query
    parameter*; it's a `NAME=VALUE` pair
    that's appended to a URL in an HTTP `GET` request. In some
    contexts, however, the term can have other meanings.

parent-child or parent/child
:   Not *parent – child* or *parent—child*.

path
:   Avoid using *filepath*, *file path*, *pathname*, or *path
    name* if possible.

peer gateway
:   Don't use *on-premises gateway* when you mean a *peer gateway*.
    A peer gateway can be an on-premises device or service or another cloud
    gateway.

peer network
:   Don't use *on-premises network* when you mean a *peer network*.
    A peer network can be an on-premises network or another cloud network.

peering zone
:   Not *peer zone*.

per
:   To express a rate, use *per* instead of the division slash (/),
    unless space constraints require the use of the slash.
:   Avoid *per* in contexts other than rate units.
:   Recommended: requests per day
:   Recommended: create a policy for each
    Pod
:   Recommended: according to the style
    guide
:   Recommended: in response to your
    request
:   Not recommended: requests/day
:   Not recommended: create a policy per
    Pod
:   Not recommended: per the style guide
:   Not recommended: as per your request

performant
:   Avoid where possible. Instead, use a more precise term.
:   Recommended: an accurate machine
    learning model
:   Not recommended: a performant machine
    learning model

persist
:   Don't use as a transitive verb. It's best to avoid using as a verb at all,
    especially in [passive voice](/style/voice).
:   Recommended: To make the token
    persistent ...
:   OK: To make the token persist ...
:   Not recommended: The token is persisted
    ...
:   Not recommended: To persist the token
    ...

persistent disk
:   Not *PD*.:   Lowercase except at the start of a sentence.

    personally identifiable information (PII)
    :   Some government agencies use the less common term *personally
        identifying information*; use this alternate term only in contexts
        where you're referring to a document that uses this term.

    pets versus cattle, pets vs. cattle, pets v. cattle
    :   Don't use. Instead, use more precise terms like *persistent versus
        dynamic* or *manually configured versus automated*.

    plain text
    :   In most contexts, use *plain text*, but use *plaintext* in a
        cryptography context.

    please
    :   Don't use *please* in the normal course of explaining how to use a
        product, even if you're explaining a difficult task.
    :   Don't use the phrase *please note*.
    :   Use *please* only when you're asking for permission or
        forgiveness—for example, when what you're asking for benefits you,
        inconveniences a reader, or suggests a potential issue with a product.
    :   Recommended: If the issue persists,
        please contact your account representative.

        plugin (noun), plug-in (adjective), plug in (verb)

        PM
        

        point to
        :   Use to refer to the action of pointing the mouse pointer (focus). This
            action doesn't imply a length of time waiting for the UI to react to user
            action.
        :   This is similar to the action [hold the
            pointer over (hover)](#hold-the-pointer-over). In most cases, it's better to use the verb
            phrase *hold the pointer over* if you want the user to wait for the
            UI to react.

        POJO
        :   If you're not actually writing about a Plain Old Java Object for a Java
            audience, use *simple object*. You can write *a simple object,
            similar to a POJO in Java* if that helps your audience.

        PoP
        :   Acronym for *point of presence*.
        :   Recommended: point of presence (PoP)
        :   Not recommended: point of presence
            (POP)

        pop-up, popup
        :   Don't use.
        :   To describe a window that appears and asks for, or presents, additional
            information, use [*dialog*](#dialog).
        :   To describe a menu that rises from an interface (such as a right-click
            context menu), use *menu*.

        populate
        :   OK to use if you're writing about a process populating a table or other
            entity. If you're writing about a person, use *fill in*.
        :   Recommended: The SQL command
            populates the table with sample data.
        :   Recommended: When you have finished
            filling in the form ...
        :   Not recommended: When you have
            finished populating the form ...

        port
        :   Use *listen on* (not *to*).

        possible
        :   Don't use *possible* or *impossible* to mean *you can* or
            *you can't*.

        PostgreSQL
        :   If the UI uses the name *Postgres*, it's OK to match the UI. Don't
            use *PostgreSQL*.

        postmortem
        :   Avoid in general usage. Instead, use *retrospective*.
        :   In disaster recovery (DR) and DevOps contexts, use *blameless
            postmortem*.

        practitioner
        :   Avoid using without any supporting information to define the roles that
            you're referring to.
        :   Recommended: The framework describes
            best practices for architects, developers, administrators, and other cloud
            practitioners.
        :   Not recommended: The framework
            describes best practices for cloud practitioners.

        pre\*
        

        prebuilt
        :   Not *pre-built*.

        precapture
        :   Not *pre-capture*.

        preemptible
        :   Not *pre-emptible* or *pre-emptive*.

        pre-existing
        :   Not *preexisting*.

        preferred pronouns
        :   Don't use. Instead, use *pronouns*.

        prerecorded
        :   Not *pre-recorded*.

        pre-shared key
        :   Not *preshared key*.

        presently, at present
        :   Avoid because this word or phrase is implied. The word or phrase can also
            prematurely disclose product or feature strategy or inappropriately imply
            that a product or feature might change.
        :   See also [as of this writing](#as-of-this-writing) and
            [currently](#currently).
        :   Recommended: This setting is required.
        :   Not recommended: At present, this
            setting is required.

        press
        :   Use when referring to pressing a key or a key combination to cause an
            action to occur. Also use for mechanical buttons.
        :   For on-screen and soft (capacitive) buttons, use *tap*.
        :   Recommended: Press
            `Control+C` (or `Command+C` on macOS).

        presubmit
        :   Not *pre-submit*.

        primitive
        :   Use with caution. Don't use *primitive* in a disparaging sense.

        pros
        :   Don't use. Instead, use a more precise term, such as *advantages*.

### Q

quick, quickly
:   What might be quick for you might not be quick for others. Try
    eliminating this word from the sentence because usually the same meaning
    can be conveyed without it.

quota
:   In API contexts, often refers to API usage limits. Where possible, it's
    best to use a more specific term, such as *usage limit*; the word
    *quota* means many different things to many different people.

### R

read-only
:   Not *read only*. Always hyphenate *read-only*.

recents screen
:   In Android contexts, use instead of *overview screen*.

redline
:   Don't use as a verb. Instead, use precise terms appropriate to the
    context.
:   In the context of editing or providing a review, refer to those actions or
    to *tracking changes*.
:   In the context of setting priorities and planning work, refer to those
    actions or to *priority lining*.

regex
:   Don't use. Instead, use *regular expression*.

repo
:   Don't use. Instead, use *repository*.

Representational State Transfer
:   Don't use. To people unfamiliar with REST, this acronym expansion is
    meaningless; it's better to refer to it as REST and not explain what it
    stands for.

reservation, off the
:   Don't use.

resource record set
:   Not *resource recordset*.

retarded
:   Don't use. If you are referring to a system or component being slowed,
    use the word *slowed*.

retriable, triable
:   Don't use *retriable* or *triable*, unless a code item uses that
    spelling. Outside of code font, write around the term.

retryable, tryable
:   Where possible, write around *retryable* and *tryable*. For
    example, write out *you can try it again* or *can be tried
    again*.

review
:   If you mean "read, potentially for the first time," then use *read*
    instead of *review*.
:   If you mean "read critically, commenting on problems" (as in *code
    review*), then *review* is fine.
:   Avoid using phrasing like "If you've never heard of OAuth, then review the
    OAuth documentation."

RFC
:   When referencing an RFC specification, use a space between *RFC* and
    the number (for example, *RFC 2318*).

roll out
:   Don't use to mean a sudden or instantaneous launch. If you use *roll
    out*, define what you mean. When possible, use a more precise,
    non-figurative term like *gradual*, *in stages*, *phases*,
    or *progressive*.

RTFM
:   Don't use. Instead, use a more precise phrase like "For more information,
    see ...."

runbook
:   Not *run book*.

runtime, run time
:   Use the noun *runtime* when referring to the environment in which
    software runs, such as a Ruby or Java runtime.
:   Use the noun phrase *run time* when referring to the time during
    program execution when something occurs, as contrasted with *compile
    time*, for example.
:   Recommended: The profiler collects
    data at run time, and the scheduler uses this data at compile time to
    improve performance for subsequent runs.
:   Recommended: The App Engine standard
    environment has two generations of runtime environments. The
    second-generation runtimes significantly improve the capabilities of App
    Engine.

### S

SaaS
:   Write out on first mention: *software as a service (SaaS)*.

sane
:   Don't use. Instead use a word like *valid* or *sensible*.

sanity check
:   Don't use. Instead, use a term like *quick check*, *confidence
    check*, *preliminary check* or *coherence check*.

scale
:   Don't use *scale* alone to say that something is large or increasing.
    Include supporting words to indicate magnitude or direction of change in
    magnitude, whether scaling up or down, such as when you change a machine
    type to add or remove CPUs or RAM, or scaling out or in, such as adding or
    removing instances from a group.
:   Recommended: The system performs
    better at a larger scale.
:   Not recommended: The system performs
    better at scale.
:   Recommended: The system scales up
    quickly, but it scales down more slowly.
:   Not recommended: The system scales
    quickly.

screenshot (noun)
:   Not *screen shot* or *screensnap*.
:   Don't use as a verb; instead, use *take a screenshot*.

scroll
:   OK to use *scroll* as a verb, but if possible, instead use a term
    that isn't specific to implementation. For example, write *go to the
    section*, instead of *scroll to the section*.
:   If you use *scroll*, don't use directional language
    like *scroll up*.A
A
see
:   OK as a general term and when referring to links and cross-references. Our
    research indicates that language relating to sight is OK for a wide range
    of readers.AS

select
:   Use to describe choosing an item from among multiple options, selecting
    text, or marking a checkbox.
:   Recommended: Select **Automatically
    check for updates**.
:   Not recommended: Check
    **Automatically check for updates**.
S
sexy
:   Don't use. Instead, use precise, positive words, such as *fast*,
    *powerful*, or *elegant*.

SHA-1
:   Not *SHA1*, except in string literals/enums and in hyphenated phrases
    such as *HSA-SHA1*.

shall
:   Avoid *shall* except under advice from a lawyer.

should, should be
:   Generally avoid.
:   Because *should* is ambiguous by definition, it can be problematic.

sign-in (noun or adjective), sign in (verb)
:   Not *log in* or *signin*.

sign into
:   Don't use. Instead, use *sign in to*.

sign-on, sign on
:   Don't use either form on its own. Use the hyphenated version as part of
    *single sign-on*.

sign-out (noun or adjective), sign out (verb)
:   Not *log out* or *signout*.

simple, simply
:   What might be simple for you might not be simple for others. Try
    eliminating this word from the sentence because usually the same meaning
    can be conveyed without it.

since
:   If you mean *because*, then use *because* instead of
    *since*. *Since* is ambiguous; it can refer to the passage of
    time. *Because* refers to causation or the reason for something.

single most
:   Not *singlemost*.

single pane of glass
:   Avoid. This term is used to favorably compare a centralized control and
    monitoring interface against the alternative of several disparate
    interfaces. It can almost always be replaced by *single interface* or
    *unified interface*.

single sign-on (noun or adjective)

slave
:   Don't use. Instead, use alternative terms appropriate to your domain, such
    as *worker* or *replica*.
:   If you're replacing the terms *master* and *slave* together,
    then consider such combinations as *primary*/*secondary*,
    *primary*/*replica*, *original*/*replica*,
    *controller*/*worker*, *initiator*/*responder*,
    *mixer*/*leaf*, *aggregator*/*collector*,
    *publisher*/*subscriber*, *leader*/*follower*, and
    *active*/*standby*.
:   If the command or code that you're documenting uses the literal word
    *slave*, then use this word only in direct reference to the code item
    ([formatted as code](/style/code-in-text)), make it clear what
    you're referring to, and use the new term thereafter. For example, "Invoke
    the secondary (`slave`) process directly when debugging issues
    between the primary and secondary processes."

slice and dice
:   Don't use the phrase *slice and dice*. Instead, use specific terms
    appropriate to the task that you're describing. Some possible options
    include: *segment data for analysis* or *break information into
    smaller parts*.

smartphone, smart phone
:   Don't use. Instead, use [*mobile phone*](#mobile) or
    *phone*. If you're talking about more than phones, then use *mobile
    device*. It's OK to use *phone* (without *mobile*) when the
    context is clear.

soon
:   Avoid in timeless documentation because this word can become outdated. The
    word can also prematurely disclose product or feature strategy or
    inappropriately imply that a product or feature might change.
:   See also [eventually](#eventually) and
    [future](#future).
:   Recommended: This setting is
    optional.
:   Not recommended: This setting is
    optional for existing applications but will soon be required for all
    applications.

spin up
:   As in *spin up an instance*. Avoid using *spin up* unless you're
    referring to a hard disk; instead, use a less colloquial term like
    *create* or *start*.

SQL
:   Refer to *a SQL* (pronounced "a sequel"), not *an SQL*.

ssh and SSH
:   Don't use `ssh` or SSH as a verb. SSH is a secure
    communications protocol; `ssh` is a utility.
:   Recommended: To establish an SSH
    connection, use the `ssh` command.
:   Recommended: Connect to the instance
    by using SSH.:   Not recommended: `ssh` into
        your remote shell.

    ssh'ing
    :   Don't use.
    :   Recommended: When you use
        `ssh` to log in ...

    startup (noun or adjective), start up (verb)

    static external IP address
    :   Don't use *static IP address* or *external IP address* to refer
        to static external IP addresses.

    status bar
    :   Not *statusbar* or *status-bar*.
    :   Lowercase except at the beginning of a sentence,
        heading, or list item.

    STONITH, STOMITH
    :   Avoid using
        [graphically
        violent terms](/style/inclusive-documentation#features-and-users). This acronym's letters stand for an extremely graphic
        and violent act. Instead, explain the relevant feature, such as *fence
        failed nodes*.

    style sheet
    :   Not *stylesheet*. This is the official spelling, per the World Wide
        Web Consortium (W3C).

    sub-command
    :   Not *subcommand*.

    subnet
    :   OK to use as a shortening of *subnetwork*. Use the same term consistently throughout your
        document.

    subtree
    :   Not *sub-tree*.

    subzone
    :   Not *sub-zone* or *sub zone*.

    such as versus like
    

    surface
    :   Avoid as a transitive verb; instead, use a more specific term, such as
        *make people aware of* or *expose*.
    :   Recommended: To make the audit logs
        available, you must configure the monitoring system.
    :   Not recommended: To surface audit
        logs, you must configure the monitoring system.

### T

tab
:   When referring to the sub-pages of a [console](#console), use
    *page* instead of *tab*.

table name
:   Two words. Set specific table names in code font.

tablet
:   *Tablet* is OK. If you don't know whether it's a tablet or a phone,
    use *device*.

tag

tap
:   In Android documentation, use for on-screen and soft (capacitive)
    buttons.:   Use instead of *click* when the environment is definitely a
        touch device.
    :   Use instead of *touch*. However, *touch & hold* (not *touch
        and hold*) is OK to use.
    :   For mechanical buttons, use [*press*](#press).

    tap & hold, tap and hold
    :   In Android documentation, don't use. Instead, use *touch & hold*.
        (Not *touch and hold*.)

    tarball
    :   Don't use. Instead, use *tar file*.

    target
    :   Avoid using as a verb when possible, especially in reference to people.
        For some readers, *target* has aggressive connotations. Instead of
        "targeting" audiences, we try to attract them or appeal to them or make
        their lives easier.
    :   It's OK to use *target* as an adjective, as in *target
        audience*, but consider rephrasing for clarity. Alternatives
        include phrases such as *intended for*, *looking for*,
        *focused on*, and *interacting with*.

    terminate
    :   Avoid using as a synonym for *stop*. Instead, use words like
        *stop*, *exit*, *cancel*, or *end*.
    :   For a specific context where you can use *terminate* as a synonym for
        *stop*, see [Documenting
        command-line syntax](/style/code-syntax#linux-signals).:   :   In some contexts, such as telephony and networking, *terminate* has
                specific technical meanings that aren't synonyms for *stop*; in those
                contexts, you can use *terminate*.

            text box, textbox
            :   Don't use. Instead, use *box*.
            :   use
                *field* instead of *box*. For example, "In the **Instance**
                field, specify a value less than 64 characters long."

            their (singular)
            

            then
            :   Although it is common in casual usage to omit the word *then* in *if...then*
                statements, you should include helper words like *then* in technical documentation. For
                more information, see
                [Use clear, precise, and unambiguous language](/style/translation#clear-language).

            they (singular)
            :   This is our preferred gender-neutral pronoun. Whether used as singular
                or plural, it always takes the plural verb. For example, "A user
                authenticates their identity by entering their password."

            third party (noun), third-party (adjective)

            this, that
            :   Where possible, put a noun after *this* or *that* for clarity.
                If doing so results in clunky prose, then don't do it; but even then, try
                thinking about what the noun would be. If you aren't sure what noun
                *this* or *that* refers to, then consider rephrasing—
                otherwise, your reader probably won't know what noun you're referring to,
                either.

            timeframe
            :   Not *time frame*. Avoid where possible, or use an alternative such as
                *period*, *schedule*, *deadline*, or *when*. But if
                you do use it, then write it as one word.

            timeout (noun), time out (verb)

            timestamp
            :   Not *time stamp*.

            time to live
            :   Not *time-to-live*. Abbreviate as *TTL* after first use.

            time zone (noun), time-zone (adjective)

            tl;dr
            :   Don't use. Instead, use something like *To summarize*, or revise the
                sentence.

            toolkit
            :   Not *tool-kit* or *tool kit*.

            touch
            :   In Android documentation, don't use. Instead, use *tap*. However,
                *touch & hold* is OK to use.

            "touch & hold"
            :   Not *touch and hold*.

            touchscreen
            :   Not *touch screen*

            traditional
            :   If possible, use a more precise term.
            :   Recommended: Conventionally, Python
                function names are lowercase, with words separated by underscores.
            :   Not recommended: Traditionally, Python
                function names are lowercase, with words separated by underscores.
            :   Recommended: This tutorial explains
                how to migrate from an on-premises data warehouse to BigQuery.
            :   Not recommended: This tutorial
                explains how to migrate from a traditional data warehouse to BigQuery.

            transpile
            :   Not *transcompile*.

            tribal knowledge, tribal wisdom
            :   Don't use. Instead, use a less figurative term to indicate knowledge held
                by a group of people.

            trojan
            :   Lowercase when referring to malware.

            turn on
            :   In procedures, use the appropriate label and action for the
                [UI element](/style/ui-elements) that the user interacts with.
            :   For turning on or activating an option or feature, use *turn on* or
                [enable](#enable) consistently. Use the same term consistently throughout your
                document.
            :   Recommended: To turn on Magic Mode,
                follow these steps.
            :   Recommended: In **Settings**, click
                the **Magic mode** toggle to the on position.

            tutorial
            :   OK to use.

            type
            :   In general, use [enter](#enter) instead of *type* because
                there is typically more than one way to enter text than typing (such as
                pasting text or speaking).

            typically
            :   Use to describe what is usual or expected under normal circumstances.
            :   Don't use as the first word in a sentence, as doing so can leave the
                meaning open to misinterpretation.

### U

UI
:   Don't use generically to refer to a page or dashboard. Use a more specific
    term like [*page*](#page) or
    [*console*](#console). If a specific term is unavailable,
    use *web interface*.
:   Recommended: In the Google Cloud
    console
:   Recommended: On the **Cloud Tasks**
    page
:   Recommended: In the Secure Source
    Manager web interface
:   Not recommended: In the **Cloud
    Tasks** UI

unarchive
:   Don't use. Instead, use *extract*.

uncheck
:   Don't use to refer to clearing a check mark from a checkbox. Instead, use
    *clear*.
:   Recommended: Clear **Automatically
    check for updates**.
:   Not recommended: Uncheck
    **Automatically check for updates**.
:   Not recommended: Deselect
    **Automatically check for updates**.

uncompress
:   Don't use. Instead, use *extract*.

under
:   Don't use for a range of version numbers. Instead,
    use [*earlier*](#earlier).
:   Don't use to refer to a position in the UI.
:   Recommended: In the **Service account
    ID** field, enter a name.
:   Recommended: For **Service account
    ID**, enter a name.
:   Not recommended: Under **Service
    account ID**, enter a name.

Unicode
:   Not *UNICODE*.

Unix-like
:   Not *Unixlike* or *Unix like*.

Unix epoch time
:   Use instead of *Unix time* or *epoch time* to refer to a
    point in time represented as a number of seconds since the Unix epoch
    (00:00:00 UTC on January 1, 1970), ignoring leap seconds.

unselect
:   Don't use. Instead, use *clear* for checkboxes, and *deselect*
    for other UI elements.:   unsighted
        :   Don't use.

        untar
        :   Don't use. Instead, use *extract*.

        unzip
        :   Don't use. Instead, use *extract*.

        US
        :   OK to use as an abbreviation for *United States*. Don't use
            *U.S.* or *U.S.A.*

        user
        :   Use the word *user* only to refer to the user of the software that
            your reader is developing. Otherwise, address the reader as *you*
            and assume that they will complete the tasks that you're documenting. For
            more information, see [Second person and first
            person](/style/person).

        user base
        :   Not *userbase*.

        using
        :   Where *using* might have more than one interpretation, use *by
            using* to help clarify the logic of the sentence.
        :   Recommended: You can filter for data
            with specific attributes by using custom filters.
        :   Not recommended: You can filter for
            data with specific attributes using custom filters.

        UTF
        :   Include the hyphen in the names of Unicode encodings, such as
            *UTF-8*, *UTF-16*, and *UTF-32*.:   utilize, utilization
                :   Use with caution. Don't use *utilize* when you mean *use*. It's
                    OK to use *utilize* or *utilization* when referring to the
                    quantity of a resource being used.
                :   Recommended: When CPU utilization
                    exceeds 75%, the autoscaler adds more CPU resources.
                :   Recommended: To distribute network
                    traffic, use a load balancer.
                :   Not recommended: To distribute network
                    traffic, utilize a load balancer.

### V

v (abbreviating *version*)
:   Use lowercase.

via
:   Don't use.

vice versa
:   Don't use. Instead, use a phrase like *the other way around*,
    *conversely*, or *otherwise*. In some contexts, vice versa is
    unclear or imprecise because in a complex sentence it's hard to know which
    two things are swapped with each other. In such cases, make it explicitly
    clear what two things are swapped.

virtual machine (VM) instance
:   Use when first introducing virtual machines on a given page. For
    subsequent mentions, you can use *VM instance* or *VM*. See also
    [GKE node](#gke-node).

visually challenged

VLAN attachment
:   Don't use the following: *interconnect attachment (VLAN)*,
    *Interconnect attachment*, *Cloud Interconnect attachment*, or
    any variation thereof. See also
    [interconnectAttachment](#interconnect-attachment).

voila
:   Don't use.

voodoo
:   Don't use. Instead, use a term like *mysterious*, *complicated*,
    or *nondeterministic*.

vs.
:   Don't use *vs.* as an abbreviation for *versus*; instead, use
    the unabbreviated *versus*.

### W

wake lock (noun), wake-lock (adjective)

walkthrough
:   Not *walk-through*.

war room, warroom, war-room
:   Don't use. Instead, use a more precise term to describe the activity or
    team. Depending on context, possible alternatives include *rapid
    response team*, *situation response team*, *situation room*,
    *incident-management team*, or *media monitoring room*.

warm
:   When possible, avoid [jargon](/style/jargon) like *warm
    failover*, *warm standby*, and *warm spare*. If you use one
    of these phrases, define it on first use and use it consistently
    throughout the document.

we
:   Don't use *we* (or other first-person plural pronouns such as
    *our* or *us*) to address the reader who is performing the
    tasks that you're documenting. Instead, use *you*.
:   It's OK to use *we* to refer to the organization that's represented
    as the author of the document as long as the antecedent is clear.

web (lowercase)

WebAssembly, Wasm
:   Use the capitalization established in the
    [WebAssembly specification](https://webassembly.github.io/spec/core/intro/introduction.html#introduction).

web application firewall (lowercase)

webmaster, web master
:   Don't use. Instead, use a more precise term to describe the specific role,
    such as *website owner*, *website administrator*, *web content
    manager*, *owner of a site*.

web server
:   Not *webserver*.

whether
:   * To decide whether it's more appropriate to use *if* or
      *whether*, see [Grammar Girl's
      discussion of *if* and *whether*](http://www.quickanddirtytips.com/education/grammar/if-versus-whether).
    * To decide whether you need to add *or not* when using
      *whether*, see [the New York
      Times's blog post about whether (or not)](http://afterdeadline.blogs.nytimes.com/2010/03/01/whether-or-not/).

while
:   Don't use to indicate a contrast. Instead, use a more precise term, such
    as *although*.
:   OK to use to refer to a period of time.

white-box
:   Avoid using *white-box*, *whitebox*, or *white box* to
    describe monitoring and testing. Consider using a more precise term for
    clarity.

    * For monitoring, use *introspective monitoring*.* For testing, use *clear-box testing*.

white glove, white-glove, whiteglove
:   Avoid using. Instead use terms like *high-touch*, *premium*, or
    *platinum-level*.

whitehat, white hat, white-hat
:   Don't use. Instead, use precise terms for the kind of compliance, such as
    *legal*, *ethical*, or *following the rules*.

white label, whitelabel, white-label
:   Don't use. Instead, use a more precise term for your context, such as
    *unbranded*, *unlabeled*, or *blank label*.

whitelist, white list, white-list
:   Don't use.

whitelisted, white listed, white-listed
:   Don't use.

whitelisting, white listing, white-listing
:   Don't use.

whitepaper
:   Not *white paper*.
:   When possible, use a more precise term. The term *whitepaper* has a variety of
    meanings in various contexts. If you must use the term *whitepaper*, also use descriptive
    terms to provide context.

whitespace
:   Not *white space*.

wildcard
:   Not *wild card*.

will
:   Avoid. Applies equally to its past tense, *would*. See also
    [Present tense](/style/tense) and
    [Documenting future features](/style/future).

wish
:   Don't use. Instead, use a word like *want* or *need*.

with
:   Don't use *with* when expressing ownership::   Recommended: A handset that has 2 GB
        of RAM.
    :   Not recommended: A handset with 2 GB
        of RAM.
:   Don't use *with* when expressing use::   Recommended: Use the debugging tool
        to debug.
    :   Not recommended: Debug this tool with
        the debugging tool.

workload
:   The term *workload* might refer to software, like an app or
    a service; to app resources, like data and infrastructure; or to physical
    components that work together.
:   Where possible, use a more precise term to describe what you mean. If you
    use the term *workload*, define your meaning on first use as you
    normally would with jargon and other ambiguous terms.

World Wide Web
:   Don't use. Instead, use *web*.

would
:   Avoid using. Instead, use *can* where possible.
:   See also [can](#can), [could](#could),
    [may](#may), [might](#might),
    [must](#must), and [should](#should).
:   For information about clarifying who's performing an action, see
    [Active voice](/style/voice).
:   For information about tenses, see [Present
    tense](/style/tense).

### Y

ymmv
:   Don't use. Instead, use something like *Your results might vary*.

you
:   Use *you* instead of [*user*](#user) to address the
    reader of your document.

### Z
