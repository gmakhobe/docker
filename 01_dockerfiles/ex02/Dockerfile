FROM ft-rails:on-build

EXPOSE 3000

CMD ["rails", "s", "-b", "0.0.0.0", "-p", "3000"]

# Build image in folder => docker build --tag ft-rails:on-build ft_rails/
# Clone if not available => git clone https://bitbucket.org/railstutorial/sample_app_4th_ed.git app
# Build image in current folder => docker build --tag ex02app .
# Run =>  docker run -it --rm -p 3000:3000 ex02app
