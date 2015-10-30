# Setup

    brew install libxml2 libxslt
    sudo gem install nokogiri -- --use-system-libraries --with-xml2-include=/usr/include/libxml2 --with-xml2-lib=/usr/lib

    bundle install
    bundle update
    bundle exec jekyll serve
