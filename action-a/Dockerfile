FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World New Action"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/ycs77/hello-github-actions"
LABEL "homepage"="https://github.com/ycs77"
LABEL "maintainer"="Lucas <yangchenshin77@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
