# gamulti
Multi-Domain Management Tools For GAM

GAMulti is a custom shell environment that assists in managing multiple GSuite domains with GAM.  By default GAM sets up one API key and interacts with only one GSuite domain.  GAM provides no elegant way to switch between multiple domains.  GAMulti provides commands for domain switching as well as an optional informative prompt with respect to the current active domain.  GAMulti also allows multi-user access to the same system and corresponding key repository.

The environment runs in a standard bash4 shell.  All GAMulti functions and user variables exist in .bash_gamulti and can be loaded from ./.bashrc during the shell’s init process.
