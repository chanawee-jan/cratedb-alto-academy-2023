# cratedb-alto-academy-2023

docker run --rm --name=cratedb --publish=4200:4200 --publish=5432:5432 --volume="$(pwd)/var/lib/crate:/data" crate
