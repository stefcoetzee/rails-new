      [--skip-namespace], [--no-skip-namespace]              # Skip namespace (affects only isolated engines)
      [--skip-collision-check], [--no-skip-collision-check]  # Skip collision check
  -m, [--template=TEMPLATE]                                  # Path to some application template (can be a filesystem path or URL)
      [--skip-gemfile], [--no-skip-gemfile]                  # Don't create a Gemfile
  -G, [--skip-git], [--no-skip-git]                          # Skip .gitignore file
      [--skip-keeps], [--no-skip-keeps]                      # Skip source control .keep files
  -M, [--skip-action-mailer], [--no-skip-action-mailer]      # Skip Action Mailer files
      [--skip-action-mailbox], [--no-skip-action-mailbox]    # Skip Action Mailbox gem
      [--skip-action-text], [--no-skip-action-text]          # Skip Action Text gem
  -O, [--skip-active-record], [--no-skip-active-record]      # Skip Active Record files
      [--skip-active-job], [--no-skip-active-job]            # Skip Active Job
      [--skip-active-storage], [--no-skip-active-storage]    # Skip Active Storage files
  -P, [--skip-puma], [--no-skip-puma]                        # Skip Puma related files
  -C, [--skip-action-cable], [--no-skip-action-cable]        # Skip Action Cable files
  -S, [--skip-sprockets], [--no-skip-sprockets]              # Skip Sprockets files
  -J, [--skip-javascript], [--no-skip-javascript]            # Skip JavaScript files
      [--skip-jbuilder], [--no-skip-jbuilder]                # Skip jbuilder gem
      [--skip-system-test], [--no-skip-system-test]          # Skip system test files
      [--skip-bootsnap], [--no-skip-bootsnap]                # Skip bootsnap gem
      [--dev], [--no-dev]                                    # Set up the application with Gemfile pointing to your Rails checkout
      [--edge], [--no-edge]                                  # Set up the application with Gemfile pointing to Rails repository
      [--master], [--no-master]                              # Set up the application with Gemfile pointing to Rails repository main branch
      [--rc=RC]                                              # Path to file containing extra configuration options for rails command
      [--no-rc], [--no-no-rc]                                # Skip loading of extra configuration options from .railsrc file


  -B, [--skip-bundle], [--no-skip-bundle]                    # Don't run bundle install
  -r, [--ruby=PATH]                                          # Add path to the Ruby binary of your choice
  --webpacker, [--webpack=WEBPACK]                           # Preconfigure Webpack with a particular framework (options: react, vue, angular, elm, stimulus)
      [--skip-webpack-install], [--no-skip-webpack-install]  # Don't run Webpack install
      [--api], [--no-api]                                    # Preconfigure smaller stack for API only apps
      [--minimal], [--no-minimal]                            # Preconfigure a minimal rails app
  -d, [--database=DATABASE]                                  # Preconfigure for selected database (options: mysql/postgresql/sqlite3/oracle/sqlserver/jdbcmysql/jdbcsqlite3/jdbcpostgresql/jdbc)
                                                             # Default: sqlite3
      [--skip-turbolinks], [--no-skip-turbolinks]            # Skip turbolinks gem
      [--skip-spring], [--no-skip-spring]                    # Don't install Spring application preloader
      [--skip-listen], [--no-skip-listen]                    # Don't generate configuration that depends on the listen gem
  -T, [--skip-test], [--no-skip-test]                        # Skip test files
