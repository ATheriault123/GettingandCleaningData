run_analysis.R
  Rows 9-16, reads in the data and assigns it to the appropriate variables
  
  Rows 18-21 then begins to merge the data by combining the Train and Test X/Y sets.
  Once the X and Y data sets are combined, 'labels' combines the train and test subject sets,
  which could then be combined all together in df.
  
  Rows 23-24 simply select just the data regarding the averages and standard deviations,
  then adds labels by associating their number variables to actlabels, which returns the description
  
  Rows 27-36 replace any kind of abbreviations with a full description to help with readability
  
  Rows 39-42, takes df, averages each variable by each activity and subject then writes a table with the data called 'data.txt
  