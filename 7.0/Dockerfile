FROM php:7.0-cli
ADD http://get.sensiolabs.org/security-checker.phar /usr/local/bin/security-checker
CMD ["security-checker","security:check","/composer.lock"]
