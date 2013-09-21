# `top` - Pluto Planet Template Pack

## What's Pluto?

Pluto is a feed reader that lets you build web pages from published
web feeds. More [Pluto Project Site »](https://github.com/feedreader/pluto)


## Usage

### Try It Yourself - How To Use the Top Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ pluto install top

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.pluto/templates
    $ git clone git://github.com/feedreader/pluto.top.git

To check if the new template got installed, use the `list` command:

    $ pluto list

Listing something like:

    Installed templates include:
       top (~/.pluto/top/top.txt)

Showtime! Let's use the `-t/--template` switch to build a sample Planet Ruby. Example:

     $ pluto build ruby.yml --template top     or
     $ pluto b ruby -t top

Open up the generated planet page `ruby.html` in your browser. Voila. That's it.


## License

The `pluto` scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.
