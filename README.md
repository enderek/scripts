nfstop - simple tool for monitoring nfs activity 

-----------------------------------------------------------------------------

tbg - simple text graph, example "sar -q":

    Max: 4.06	Step: 0.309
    ..........................................#..............		 4.06
    .........................................###.............		 3.75
    .........................................###.............		 3.44
    ........................................#####............		 3.13
    ........................................#####............		 2.82
    .......................................######............		 2.51
    ........#..............................#######...........		 2.21
    ........#..............................#######...........		 1.90
    ........#.................#............#######..........#		 1.59
    .#......#...........#.....#...##......########..........#		 1.28
    000000000000000000000000000000000000000000000000000000000
    000000111111222222333333444444555555666666777777888888999
    :::::::::::::::::::::::::::::::::::::::::::::::::::::::::
    012345012345012345012345012345012345012345012345012345012
    555555555555555555555555555555555555555555555555555555555
    :::::::::::::::::::::::::::::::::::::::::::::::::::::::::
    000000000000000000000000000000000000000000000000000000000
    111111111111111111111111112111111111111111111111111111111
                                                         

    Min: 0.97

-----------------------------------------------------------------------------

utextgraph - new version of tbg :)
txt graph with UTF characters,
example:

    sar -q |head -50 | utextgraph
    Min: 0.40       Max: 2.98       Step: 0.3225
    ▁▁▁▁▁▁▁▁▄▅▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▂▆█▅▁▁▁▁▁

-----------------------------------------------------------------------------

japh - just another perl hacker, dirty and ugly oneliner :)

-----------------------------------------------------------------------------

some_ways_to_get_linux_ip_address - list of commands return ip address
