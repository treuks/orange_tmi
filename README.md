# orange_tmi

Small and stupid TMI message parser written in very naiive Gleam


## How to run the Benchmarks:

After you're in the code directory, run:
```sh
    gleam clean && \
    gleam build && \
    erl -pa ./build/dev/erlang/*/ebin -noshell -eval 'orange_tmi@@main:run(benchmark)'
```