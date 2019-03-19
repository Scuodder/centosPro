FROM consol/centos-xfce-vnc

ENV REFRESHED_AT 2018-03-18


# switching to root user to install wine 
USER 0


#RUN yum install epel-release && yum clean all
#rm -rf /var/cache/yum
RUN yum install wine -y && yum clean all
#REMOVE -rf /var/cache/yum


#switching back to some random user to disable root priviledges to make deployment process #on openshift possible 
USER 1000 





