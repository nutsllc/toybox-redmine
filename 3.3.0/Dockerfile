FROM redmine:3.3.0
MAINTAINER NutsProject,LLC

COPY docker-entrypoint-ex.sh /entrypoint-ex.sh
ENTRYPOINT ["/entrypoint-ex.sh"]
CMD ["rails", "server", "-b", "0.0.0.0"]
