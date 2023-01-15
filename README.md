# livebook-snippets

My personal Elixir/Phoenix bible. A collection of markdown files that are compatible with Livebook.


# Instructions

Requires Docker to be installed. Just run `docker-compose up` to get started.


# Authentication

By default, the password is `password1234`. There are 2 ways to override the password:
  - (Recommended) Create a `.env` file in the root directory of the project with the environment variable `LIVEBOOK_PASSWORD=your_desired_password`
  - (Not recommended) Override the `docker-compose.yml` file so that the default value for `LIVEBOOK_PASSWORD` is no longer `password1234`
    - If you edit the password here, it will end up in your git repository.
