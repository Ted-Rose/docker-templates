FROM php:8.3-fpm-alpine

# Set working directory
WORKDIR /var/www/public

# Copy the php application files to the container
COPY ./index.php .

# Expose port 9000
EXPOSE 9000

# Start PHP-FPM
CMD ["php-fpm"]
