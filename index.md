Using GIT with Wolfram Mathematica

It is importante to disable the "file outline cache" and "Cell time change", which is the metadata of the notebook as it  can cause merge conflicts if multiple parties are editing the same notebook. This is easily disabled with the Option Inspector.
In the Mathematica menu, go to Format >> Option Inspector, in the top - left set the scope dropdown to Selected Notebook and search for FileOutlineCache and TrackCellChangeTimes in the search field.Set the option to False and save your notebook.