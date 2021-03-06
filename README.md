General_Eco-Evo_Model (GEM)
==========================

GEM is used to study evolutionary ecological systems of an arbitrary number of predator and prey species.  Parameter values are user-defined in a json-format configuration file.  The program is run using the following command:

    python bin/general_eco-evo_model.py my_config.json

Configuration files can be saved anywhere, but it is convenient to store them in **config/**.  Depending on the number of species defined in the configuration file, as well as the types of parameters specified, the resulting graphs are saved in

    | graphs/system_model/uxv/YYMMDD_HHMMSS/

where **u** represents the number of predator species, **v** represents the number of prey species, and **YYMMDD_HHMMSS** is a date-time stamp of when calculations began on that specific parameter set.  **system_model** is the either the null model, variable growth only, variable capacity only, or the 'full' model.  Multiple parameter sets can be defined in a single configuration file.

The following command will show the usage:

    python bin/general_eco-evo_model.py -h

Any and all questions regarding this software can be sent to Samuel Fleischer at **SamFleischer@ucdavis.edu**.
