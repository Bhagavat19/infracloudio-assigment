FROM infracloudio/csvserver:latest
copy ./gencsv.sh /csvserver/ 
VOLUME /home/ec2-user/csvserver/solution:/csvserver
EXPOSE 9093
EXPOSE 9300
EXPOSE 9393
RUN ./gencsv.sh \
  &&  chmod 755 /csvserver/* \

