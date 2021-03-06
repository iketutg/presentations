# Presentations from Brandon Mitchell

These slides are made with RemarkJS and should be viewable in any browser. From
the desktop, you can press "P" to see presenter notes. PDF's have also been
included when possible. For the slides with a live terminal, use "W" and "E" to
pause/play the recording.

## Docker Build

Covering multi-stage, buildkit, buildx, and multi-architecture images from the
perspective of a Go user.

- [Presentation](https://sudo-bmitch.github.io/presentations/docker-build/presentation.html)

## DC2019 - Tips and Tricks From The Docker Captains

- [Original presentation](https://sudo-bmitch.github.io/presentations/dc2019/tips-and-tricks-of-the-captains.html)
  [[Download pdf](https://sudo-bmitch.github.io/presentations/dc2019/tips-and-tricks-of-the-captains.pdf)]

- [Extended presentation](https://sudo-bmitch.github.io/presentations/dc2019/tips-and-tricks-of-the-captains-extended.html)

## BSides NoVA - Containing Security Vulnerabilities with Containers

- [Presentation](https://sudo-bmitch.github.io/presentations/bsides-nova/presentation.html)

## DC2018 EU - Tips and Tricks From A Docker Captain

- [Original presentation](https://sudo-bmitch.github.io/presentations/dc2018eu/tips-and-tricks-of-the-captains.html)
  [[Download pdf](https://sudo-bmitch.github.io/presentations/dc2018eu/tips-and-tricks-of-the-captains.pdf)]

- [Extended presentation](https://sudo-bmitch.github.io/presentations/dc2018eu/tips-and-tricks-of-the-captains-extended.html)
  [[Download pdf](https://sudo-bmitch.github.io/presentations/dc2018eu/tips-and-tricks-of-the-captains-extended.pdf)]

Note, this talk is from DockerCon 2018 EU and is a continuation on the
"Tips and Tricks of the Docker Captains" theme that was first started by
Captain [Adrian Mouat](https://twitter.com/adrianmouat). Check out [his talk
from DockerCon 2018 in San Francisco](https://drive.google.com/file/d/1RBAl2PfTnn-IZWzQEoiISaXh4GQOpjxL/view).

There was also a webinar given based on the above talk. Slides are almost identical to those above:
- [Webinar presentation](https://sudo-bmitch.github.io/presentations-webinar-20181212/dc2018eu/tips-and-tricks-of-the-captains.html)

## DC2018 - Frequently Asked Queries from StackOverflow

- [Full presentation](https://sudo-bmitch.github.io/presentations/dc2018/faq-stackoverflow.html)
  [[Download pdf](https://sudo-bmitch.github.io/presentations/dc2018/faq-stackoverflow.pdf)]

- [Lightning talk](https://sudo-bmitch.github.io/presentations/dc2018/faq-stackoverflow-lightning.html)
  [[Download pdf](https://sudo-bmitch.github.io/presentations/dc2018/faq-stackoverflow-lightning.pdf)]

## Asciinema

- I use the player from: https://github.com/asciinema/asciinema-player
- The follow commands are used to build a recording:
  ```
  # Install asciinema:
  apt-get install asciinema
  # Setup a window:
  tmux new-session -s preso
  # Tip: set PS1='\$ ', set window size to: 100x26 with `printf '\e[8;26;100t'`
  # After windows are setup, detach from tmux (Ctrl-B D)
  # Create a recording:
  asciinema rec name.cast -i 3 -c "tmux attach -t preso"
  # Stop the recording by detaching (Ctrl-B D)
  # Tip: Edit the recording to remove the last few milliseconds of the detach
  # Replay the recording:
  asciinema play name.cast
  ```

## License

[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public
License](LICENSE)

