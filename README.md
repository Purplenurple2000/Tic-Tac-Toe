public class TicTacToe {
	char square [];
	void board() {
		System.out.println ("\n Tic Tac Toe " );
		System.out.println (" Player 1 is X     Player 2 is 0 \n");
		System.out.println ("     |     |     ");
		System.out.println ("  " + square [1] + "  |  " + square [2] + "  |  " + square [3]);
		System.out.println ("_____|_____|_____");
		System.out.println ("     |     |     ");
		System.out.println ("  " + square [4] + "  |  " + square [5] + "  |  " + square [6]);
		System.out.println ("_____|_____|_____");
		System.out.println ("     |     |     ");
		System.out.println ("  " + square [7] + "  |  " + square [8] + "  |  " + square [9] );
		System.out.println ("     |     |     ");
	}
	
	int checkwin() {
		if (square [1] == square [2] && square [2] == square [3])
			return 1;
		else if (square [4] == square [5] && square [5] == square [6])
			return 1;
		else if (square [7] == square [8] && square [8] == square [9])
			return 1;
		else if (square [1] == square [4] && square [4] == square [7])
			return 1;
		else if (square [2] == square [5] && square [5] == square [8])
			return 1;
		else if (square [3] == square [6] && square [6] == square [9])
			return 1;
		else if (square [1] == square [5] && square [5] == square [9])
			return 1;
		else if (square [3] == square [5] && square [5] == square [7])
			return 1;
		else if (square [4] == square [5] && square [5] == square [6])
			return 1;
		else if (square [1] != '1' && square [2] != '2' && square [3] != '3' && square [4] != '4' && square [5] != '5' && square [6] != '6' && square [7] != '7' && square [8] != '8' && square [9] != '9')
			return 0;
		else 
			return -1;
		
	
	}
	
	public static void main(String[] args) {
		int player =1,i, choice;
		
			
		}
			
		
	
		

	}
