## The default template for [Telegram](https://telegr.am) sites

This template is the default template for Telegram sites.  It's based on 
[Twitter Bootstrap](http://twitter.github.com/bootstrap/) with modifications
and enhancements based on [Addy Osmani's](http://addyosmani.github.com/jquery-ui-bootstrap/) stuff.

Include this template in your site by putting the following line
at the top of your `index.md` file:

    template_url:  https://github.com/telegr-am/template-base.git

So that your `index.md` looks something like:

    template_url:  https://github.com/telegr-am/template-base.git
    
    # Hello
    
    I am a page

Alternatively, you can put it in Hoisted's faux reference extra info format:

    # Hello
    
    I am a page
    
    [template_url: https://github.com/telegr-am/template-base.git]: /

You can also fork the template and change it up to your heart's content and then
use the `template_url` extra info to point to your public GitHub repository
with the template in it.

We will also gladly accept pull requests if there are fixes or enhancements to this
template.

Rock and Roll!
