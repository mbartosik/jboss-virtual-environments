#
#
#
FROM jboss_fsw/sy
MAINTAINER jmorales <jmorales@redhat.com>

# Expose the required port
EXPOSE 8080 9990 9999 8787

# Start FSW
CMD ["/home/jboss/jboss-eap-6.1/bin/standalone.sh", "-c", "standalone-ha.xml", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]
