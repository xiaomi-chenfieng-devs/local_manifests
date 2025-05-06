To initialize your local repository use
---------------------------------------

    git clone https://github.com/xiaomi-chenfieng-devs/local_manifests.git -b main .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j14 --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
