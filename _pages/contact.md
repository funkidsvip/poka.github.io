---
title: "联系Poka一家"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">请在下方邮件联系{{site.name}}. 我们将尽快回复!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="昵称*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="邮件地址*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="内容*" required></textarea>    
<input class="btn btn-success" type="submit" value="发送">
</form>