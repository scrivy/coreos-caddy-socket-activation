# coreos-caddy-socket-activation

This demo builds upon [eriksjolund's caddy socket activation](https://github.com/eriksjolund/podman-caddy-socket-activation) but with an additional CoreOS [butane](https://coreos.github.io/butane/) config. Fedora's [CoreOS](https://fedoraproject.org/coreos/) aids in bootstrapping virtual machines.

I did it this way to make it easy to put caddy in a [DMZ](https://en.wikipedia.org/wiki/DMZ_\(computing\)).

## To generate the ignition file

* Clone this repository
* Acquire [butane](https://coreos.github.io/butane/getting-started/)
* Run `./butane.sh > coreos.ign`

## To launch the virtual machine

I'll eventually write a post but until then see [this blog post](https://danielscrivano.com/blog/posts/nightscout/) for one example of how you might launch an ignition file using libvirt.
