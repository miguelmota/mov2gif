# mov2gif

> A bash script to convert QuickTime movie (.mov) to animated gif (.gif)

## Dependencies

- ffmpeg
- gifsicle

## Install

```
wget https://raw.githubusercontent.com/miguelmota/mov2gif/master/mov2gif.sh
chmod +x mov2gif.sh
mv mov2gif.sh /usr/local/bin/mov2gif
```

## Usage

```bash
mov2gif -i <input.mov> -o <outout.gif>
```

### Example

```bash
mov2gif -i screencast.mov -o output.gif
```

30FPS (default is 10FPS)

```bash
mov2gif -f 30 -i screencast.mov -o output.gif
```

## License

MIT
