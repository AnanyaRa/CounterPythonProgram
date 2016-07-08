# CounterPythonProgram
This program takes a nucleotide sequence as a string, and prints the ratio that shows the amount of each nucleotide letter. (A,C,T,G)


S="ATATGCT"

a=0

t=0

c=0

g=0

for i in S:
                if i=="A":
                    a=a+1
                
                elif i=="T":
                    t=t+1
                
                elif i=="C":
                    c=c+1
                
                elif i=="G":
                    g=g+1


print (float(a)/float(len(S)))

print (float(t)/float(len(S)))

print (float(c)/float(len(S)))

print (float(g)/float(len(S)))
                
