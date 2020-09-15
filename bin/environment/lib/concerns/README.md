This CLI project helps the user to discover new classical music scores!

I can use IMSLP API here: https://imslp.org/wiki/IMSLP:API

The work flow should be:
    1. greet the user
    2. ask the user what they would like to know more about:
        A. a work (title) 
            1. if they enter 'work' give the user options of:
                a. a link to the score 
                b. give the user information about that work:
                    i. genre
                    ii. composer
                    iii. composer dates
                    iv. instrumentation
                    v. form
            2. then they are asked if they would like to know more works of this:
                a. genre
                b. composer
                c. instrumentation
        B. a form (i.e. sonata, symphony, opera, etc.)
            1. if they enter 'form' give the user options of:
                a. a list of a requested number of examples (top examples?), i.e. top 5 sonatas
                    i. :number
                    ii. :composer
                    iii. :genre
        C. a composer (last_name, first_name = nil)
            1. if they enter 'composer' give the user options of:
                a. a list of a requested number of (examples = 5 )(top examples?), i.e. top 5 works
                    i. :works
                    ii. :genre
                    iii. :form   
        D. a genre (time period)
            1. if they enter 'genre':
                a. give the user a list of all genres of that composer


    
