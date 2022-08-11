## malgo
[![Build Status](https://github.com/edaniels/malgo/actions/workflows/build.yml/badge.svg)](https://github.com/edaniels/malgo/actions)
[![GoDoc](https://godoc.org/github.com/edaniels/malgo?status.svg)](https://godoc.org/github.com/edaniels/malgo) 
[![Go Report Card](https://goreportcard.com/badge/github.com/edaniels/malgo?branch=master)](https://goreportcard.com/report/github.com/edaniels/malgo) 
<!--[![Go Cover](http://gocover.io/_badge/github.com/edaniels/malgo)](http://gocover.io/github.com/edaniels/malgo)-->

Go bindings for [miniaudio](https://github.com/dr-soft/miniaudio) library.

Requires `cgo` but does not require linking to anything on the Windows/macOS and it links only `-ldl` on Linux/BSDs.

### Installation

    go get -u github.com/edaniels/malgo

### Documentation

Documentation on [GoDoc](https://godoc.org/github.com/edaniels/malgo). Also check [examples](https://github.com/edaniels/malgo/tree/master/_examples).

### Platforms

* Windows (WASAPI, DirectSound, WinMM)
* Linux (PulseAudio, ALSA, JACK)
* FreeBSD/NetBSD/OpenBSD (OSS/audio(4)/sndio)
* macOS (CoreAudio)
* Android (OpenSL|ES, AAudio)
