# go-openai

Wrapper around https://github.com/sashabaranov/go-openai

## Basic Info

I wrapped the above named repo because I need to enhance structs until the devs on that project do it themselves. Not much else to it.

I'll keep the release tag versions here in line with the ones in the forked repo.

------

## Tag Versions

The release tag is generated each time based on this format (standard Go pseudo version format):

```
VERSION={Forked repo release number}
echo "v$VERSION-$(git show -s --format=%cd --date=format:%Y%m%d%H%M%S)-$(git rev-parse --short=12 HEAD)"
```

...where `{Forked repo release number}` is replaced with a SemVer value.

For example:

```
VERSION=1.17.9
echo "v$VERSION-$(git show -s --format=%cd --date=format:%Y%m%d%H%M%S)-$(git rev-parse --short=12 HEAD)"
```
