# docker-magiminer
[MAGI coin](http://www.m-core.org) cpu-only miner docker container

This container image allows you to mine MAGI coin (ticker symbol: XMG), exploiting just your CPU in a energy efficient way.

For more info, go to the official [MAGI Resource](http://www.m-core.org/resources) page.

To start using it:

    docker run --rm -t -i giodegas/magiminer /sbin/my_init -- bash -l
    
Then launch your miner as decribed in the [MAGI miner repository](http://github.com/magi-project/m-cpuminer-v2).


