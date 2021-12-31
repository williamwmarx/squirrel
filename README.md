# squirrel
Stash large datasets on GitHub for free, quick, and easy download 🐿

## Install
To install `squirrel`, run the following:
```bash
curl ...
```

## Usage
### Create a stash
Creating a stash is simple. The following command will launch a dialog walking you through its
creation.
```bash
squirrel new
```

You can also define a stash’s name and content during creation.
```bash
squirrel new [STASH NAME] [FILE PATH(S)]
```

## Add files to stash
Adding a file or files to a stash is simple.
```bash
squirrel stash [FILE(S)]
```
If the file is located inside an existing stash, it will be added to it by default. Otherwise,
`squirrel` will interactively ask you which stash you wish to add the file to.

You can also pass a stash name directly for non-interactive use.
```bash
squirrel stash -n [STASH NAME] [FILE PATH(S)]
```

## Remove files from stash
Removing files is as simple as adding them.
```
squirrel rm [FILE(S)]
```

## Purge all traces of files
Repository size can be reduced by purging files both from a stash and from the stash’s history.
```
squirrel purge [FILE(S)]
```
