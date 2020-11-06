Content-Type: text/plain; charset="utf-8"
MIME-Version: 1.0
Content-Transfer-Encoding: 7bit
Subject: Password reset on 127.0.0.1:8000
From: webmaster@localhost
To: jeddou.google@gmail.com
Date: Fri, 06 Nov 2020 16:17:11 -0000
Message-ID: <1604679147241924@>

Someone asked for password reset for email jeddou.google@gmail.com. Follow the
link below:
http://127.0.0.1:8000{% url "password_reset_confirm"
uidb64=uid token=token %}
Your username, in case you've forgotten: jeddou
-------------------------------------------------------------------------------
[06/Nov/2020 17:17:12] "POST /password_reset/ HTTP/1.1" 302 0
[06/Nov/2020 17:17:12] "GET /password_reset/done/ HTTP/1.1" 200 519