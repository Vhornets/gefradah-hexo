title: Contact
tiny: true
cover: releases/dead-state-best-conditions-booklet/bucklet2.jpg
date: 2015-08-16 14:44:12
---
{% raw %}
<div class="form">
    <h3 class="form__title">
        Send me a proposition or just say hi.
    </h3>

    <form class="form-stacked js-send-form" action="//formspree.io/vhornets@gmail.com" method="post">
        <div class="form-group">
            <input type="text" name="name" class="form-control" placeholder="Your name">
        </div>

        <div class="form-group">
            <input type="text" name="_replyto" class="form-control" placeholder="E-mail" required>
        </div>

        <div class="form-group">
            <textarea name="message" rows="6" class="form-control" placeholder="Your message" required></textarea>
        </div>

        <div class="form-group">
            <input type="hidden" name="_next" value="//gefradah.com" />
            <input type="hidden" name="_subject" value="Gefradah: new message from user" />
            <input type="text" name="_gotcha" style="display:none" />
            <input type="submit" class="btn btn-default" value="SUBMIT" />
        </div>
    </form>
</div>
{% endraw %}