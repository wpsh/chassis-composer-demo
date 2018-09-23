Demo of using [Chassis](https://github.com/Chassis/Chassis) as [a Composer dependency](https://github.com/Chassis/Chassis/issues/481).

- Uses a local `Vagrantfile` that simple loads the Chassis `Vagrantfile` from the `vendor/chassis/chassis` directory.

Currently it doesn't work because Chassis looks for `config.local.yaml` override in the same directory as the original `Vagrantfile`.
