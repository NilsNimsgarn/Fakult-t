# Fakult-t
module main
sub main()
dim anzahl as integer=console.readline()
dim zahlenreihe as string=console.readline()
dim zahl()as string=split(zahlenreihe)

console.writeline(factorial(zahl(anzahl-1)))
end sub

Public Function Factorial(ByVal x As Integer) As Integer
        If x <= 1 Then
            Return 1
        Else
            Return x * Factorial(x - 1)
        End If
 End Function

end module
