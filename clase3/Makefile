# Define input jupyter notebook to be converted into slides
# By default, output file is named after the input_notebook
input_notebook = clase3.ipynb

slides: $(input_notebook)
	jupyter nbconvert $(input_notebook) --to slides \
	--no-prompt --TagRemovePreprocessor.remove_input_tags {\"to_remove\"} \
	--post serve --SlidesExporter.reveal_theme=simple

