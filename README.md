# Transpose-of-Matrix
You are given a NXN matrix. You need to find the transpose of the matrix.
Scanner sc = new Scanner(System.in);

		int n = sc.nextInt();
	
		int mat[][] = new int[n][n];
		for(int i=0; i<n; i++){
			for(int j=0; j<n; j++){
				mat[i][j] = sc.nextInt();
			}
		}
		for(int j=0; j<n; j++){
			for(int i=0; i<n; i++){
				System.out.print(mat[i][j] + " ");
			}System.out.println();
		}
