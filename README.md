# home_assistant_stuff

## scripts

- Ashley's Light Fader to run my wake-up light in the morning. I did not create this, all credits go
  to [Ashley](https://community.home-assistant.io/t/ashley-s-light-fader-2-01-fade-lights-and-or-color-temperature-with-your-choice-of-easing-curves-including-ease-in-ease-out-and-ease-in-out/584077).

  This is the most recent version + some changes:
    - have defaults for ints and floats
    - replace `data_template` with `data`
    - sometimes we fail to connect with the device in the script, so added `continue_on_error: true` everywhere
    - ran the script through gemini to check formatting and errors
