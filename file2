# import the Document class
# from the docx module
from docx import Document

# create an instance of a
# word document we want to open
doc = Document('new.docx')

# print the list of paragraphs in the document
print('List of paragraph objects:->>>')
print(doc.paragraphs)

# print the list of the runs
# in a specified paragraph
print('\nList of runs objects in 1st paragraph:->>>')
print(doc.paragraphs[0].runs)

# print the text in a paragraph
print('\nText in the 1st paragraph:->>>')
print(doc.paragraphs[0].text)

# for printing the complete document
print('\nThe whole content of the document:->>>\n')
for para in doc.paragraphs:
	print(para.text)
