to enter vim :- vim <directory>
to create a directory or enter an existing directory :- ~/.vimrc
to exit vim  :- 

	:q -> save and exit
	:qi-> exit without save
	:wq-> write and save

more basic commands :-
	i  -> to write from before the char of current curser pointer
	a  -> to write from after the cahr of current curser pointer	
	shift+i ->to insert from start of the line
	shift+a ->to insert from end of the line
	o  -> start writing in new line below current line
	shift + o -> start writing in new line above current line
	h  ->to move left
	j  ->to move down
	k  ->to move up
	l  ->to move right
	<number><direction> -> to move in a specific direction with specified steps like 5h -> moves 5 steps left 5j->moves 5 steps down 		->above command also works with arrow keys also
	u  ->undo
	ctrl+r  -> redo

	


	:set number ->set numbering for each line from start
	:set relativenumber -> set numbering for each line from current line	
	:set mouse=a ->to use mouse actively with editor
	:set tabstop=4 ->
	:set shiftwidth=4
	:set autoindent
	colorscheme slate ->sets a color scheme to our text
