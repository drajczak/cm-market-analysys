# Construction Machinery Market Analysys in Poland

The goal of this project is to prepare a database of construction machinery delivered by month in each province since 2009.

The monthly report include information on the number of machines of a given type and class in each vovoidship.

The data has been collected by different companies over the years, so the names of the files and tabs are different. The location of the valuble information in tables alone does not allow it to be used direclty for analysys, and in addition, the files contain many tabs whose naming varies over different time periods, further complicating the use of the data. On the other hand, the upside is that regardless of the period of preparation of a gicen report, the data itsefl is always in the same location of a given tab, wich allows automation of the process.

The procjec assumtion is as follows. I started by unifying the file names to organize them. Once file names are roganized, the script can recognize which tab contains data of interest.

Then when we know where to look, we can extract valuble information and turn it into a DataFrame object for further analysys and predictions of what machines will sell in given regions in the future, allowing organization for more data-driven busines decisions.
