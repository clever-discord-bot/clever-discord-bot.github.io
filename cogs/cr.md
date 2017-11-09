# Clash Royale
Clash Royale related commands

* `register|save` * Quandary/Dilemma server  
  Tag registering commands

  * `me [tags...]`
    >Registers the provided list of tags to your discord account.  
    Having used this command to register your tag is required  
    for being a member of Quandary or Dilemma.  
    Provide no tags to remove all registered tags from your account.

  * `force <member> [tags...]` * Overwatch role
    >Registers the provided list of tags to the provided member's account.  
    Functions the same as `register me`

  * `mine|my`
    >Shows what tags you have registered to your account

  * `check|get <member>`
    >Shows what tags the provided member has registered to their account

  * `who|whois <tag>`
    >Shows what member the provided tag belongs to, if any.

  * `all` * Overwatch role
    >Shows what tags every single member has registered,  
    and which members do not have any tags registered

* `cr`  
  Clash Royale commands

  * `prof|profile [tags...]`
    >Sends clash royale profile for the given tags. If no tags are provided, registered tags are used.  
    This command shows most things that are possible to get.  
    That includes:
      - Main
      - Stats
      - Chests
      - Deck
      - Clan

  * `quandary|dilemma` * Quandary/Dilemma server  
    Clan management commands for Quandary and Dilemma

    * `chest`
      >Shows clan chest stats & list for given clan
  
    * `list [sortby=trophies] [reverse=yes]`
      >Sends a list of the clan's members,  
      sorted by the *sort by* param, and reversed by the *reverse* param.  
      Some possible sorting arguments are:
        - trophies
        - crowns
        - rank
        - level
        - donations
        - registered
        - not-registered
  
  * `role|sort <member>` * Overwatch role
    >Sorts out discord roles for the provided member.  
    Fetches data from the api, checking registered tags.  
    Removes all clan roles if member has no registered tags.
  
  * `rcheck <member>` * Overwatch role
    >Checks what discord roles the provided member would have after a sort.  
    Fetches data from the api, checking registered tags.  
    Removes all clan roles if member has no registered tags.
  
  * `sortall` * Overwatch role
    >Sorts out discord roles for every member in the server,  
    according to registered tags (similar to `cr role`).  

    !> This command currently guarantees mass destruction, and is therefore disabled

  * `clan`  
    Clan information commands. `quandary` and `dilemma` can be used instead of the two clans' tags.

    * `main <clan tag>`
      >Sends main clan info of the tag.

    * `members <clan tag>`
      >Sends a list of clan's members, by tag.

    * `nmembers <clan tag> [sort by=rank] [reverse=no]`
      >New and improved clan members command.  
      Sends clan list of the clan tag, sorted by *sort by*.  
      Order can be reversed with *reverse* param.  
      Possible arguments for sorting are:
        - trophies
        - crowns
        - rank
        - level
        - donations

    * `chest <tag>`
      >Sends clan chest info for the tag.

  * `deck`  
    Deck commands, using images.

    * `fromurl|ushow <url>`
      >Shows a deck from a clash royale deck share link

    * `make|show <cards*8>`
      >Shows a deck from 8 provided cards.

    * `random|rand`
      >Shows a 100% randomly generated deck.

    * `save|new <name> <cards*8>`
        >Saves a deck made from 8 cards, to the name.