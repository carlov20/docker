FROM logstash

MAINTAINER cv

RUN logstash-plugin install logstash-codec-multiline
ADD first-pipeline.conf /logstashExample/
ADD logstash-tutorial-dataset /logstashExample/
CMD ["logstash","-f","/logstashExample/first-pipeline.conf"]
