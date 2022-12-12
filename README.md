if -then 



Public Function SC(A As Integer, B As Integer, C As Integer) As String


    Dim suma As Integer
    
    suma = A + B + C
    
    Select Case suma
        Case Is < 0
            SC = "negativo"
        Case Is = 0
            SC = "Cero"
        Case Else
            SC = "positivo"
        End Select
            

End Function
