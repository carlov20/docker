FROM logstash

MAINTAINER cv

ADD first-pipeline.conf /logstashExample/
ADD logstash-tutorial-dataset /logstashExample/
CMD ["logstash","-f","/logstashExample/first-pipeline.conf"]