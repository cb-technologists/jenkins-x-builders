FROM gcr.io/jenkinsxio/builder-rubybase:0.0.32

# jx
ENV JX_VERSION 2.0.134
RUN curl -f -L https://github.com/jenkins-x/jx/releases/download/v${JX_VERSION}/jx-linux-amd64.tar.gz | tar xzv && \
  mv jx /usr/bin/
