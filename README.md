<!-- 
     Before implementing this jekyll snippet make sure
     1. you have signed up with Mailchimp.
     2. you have created a list in Mailchimp.
     3. you have defined the list in _config.yml,
     for ex: "mailchimp-list: //redgadgets.us10.list-manage.com/subscribe/post?u=210acce5db69d3d4a04b0e25d&amp;id=08c6708f40"
-->  

<form action="{{site.mailchimp-list}}" method="post" name="mc-embedded-subscribe-form" class="wj-contact-form validate" target="_blank" novalidate>
    <div class="mc-field-group">
        <input type="email" placeholder="Email" name="EMAIL" class="required email" id="mce-EMAIL" autocomplete="on">
        <input type="submit" value="Subscribe" name="subscribe" class="heart">
    </div>
</form>

<style>
    .wj-contact-form input {
        vertical-align: middle;
        margin-top: 0.25em;
        margin-bottom: 0.5em;
        padding: 0.75em;
        font-family: monospace, sans-serif;
        border:1px solid #444;
        outline-color: #2e83e6;
        border-radius: 3px;
        transition: box-shadow .2s ease;
    }
    
    .wj-contact-form input[type="submit"] {
        background-color: #2e83e6;
        border: 1px solid #2e83e6;;
        color: #eee;
    }
</style> 
