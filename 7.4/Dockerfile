FROM php:7.4-cli
ADD https://get.sensiolabs.org/security-checker.phar /usr/local/bin/security-checker
RUN chmod +x /usr/local/bin/security-checker
CMD ["/usr/local/bin/security-checker","security:check","/composer.lock"]
