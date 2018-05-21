# NAME

Float::Truncate - Ttruncate Float decimal length by special length

# SYNOPSIS

    use Float::Truncate qw/truncate truncate_force/;

# DESCRIPTION

Float::Truncate is used for truncate float decimal length

    use Float::Truncate qw/truncate truncate_force/;

    my $float = 1.556;

    print truncate( $float, 2 );       # output 1.56
    print truncate_force( $float, 2 ); # output 1.55

    # If not special length argument, will original float number.
    print truncate( $float );          # output 1.556

# AUTHOR

MC Cheung <mc.cheung@aol.com>

# COPYRIGHT

Copyright 2018- MC Cheung

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
