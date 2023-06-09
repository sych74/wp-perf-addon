
redmilwo@ / 8lUnlUkCc3

for SW_USER_I in {10..10010}; do wp --allow-root user create "username${SW_USER_I}" "username${SW_USER_I}@example.com" --user_pass="use_a_password" --role="subscriber" --quiet; done;
