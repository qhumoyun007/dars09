# dars09
#dars009
#1
# ovqatlar=[]
# while True:
#     savol=f"menyu kiriting:"
#     a=input(savol)
#     ovqatlar.append(a)
#     takrorlash=input("tugadimi?(ha)")
#     if takrorlash=="ha":
#         print(ovqatlar)
#         break

# s=0
# n=1
# while True:
#     a=input(f"{n}-sonni kiriting:")
#     b=input("amalni kiriting:")
#     if b=="+":
#         s=float(f"{a}")+s
#         n+=1
#     if b=="=":
#         print(s)
#         break
#2
# while True:
#     a=input()
#     if a!="=":
#         b=input()
#         if b=="+":
#             if b!="=":
#                 c=float(input())
#                 print(float(a)+c)
#             else:
#                 break
#         elif b=="-":
#             if b!="=":
#                 c=float(input())
#                 print(float(a)-c)
#             else:
#                 break
#         elif b=="*":
#             if b!="=":
#                 c=float(input())
#                 print(float(a)*c)
#             else:
#                 break
#         elif b=="/":
#             if b!="=":
#                 c=float(input())
#                 if c!="0":
#                     print(float(a)/c)
#                 else:
#                     print("maxraj nolga teng bo'la olmaydi")
#             else:
#                 break
#     else:
#         break
# s=0
# n=1
# c=1
# while True:
#     a=input(f"{n}-sonni kiriting:")
#     b=input(f"{c}-amalni kiriting:")
#     c+=1
#     if b!="=":
#         n+=1
#         if b=="+":
#             s+=a
#     else:
#         print(s)
#         break
#2
# ovqat={}
# ishora=True
# while ishora:
#     ovqatlar=input("ovqat nomi:")
#     narx=input(f"{ovqatlar}ning narxi:")
#     ovqat[ovqatlar]=input(narx)
#
#     javob=input("yana ovqat qo'shasizmi?(ha yoki yoq)")
#     if javob=="yoq":
#         ishora=False
# for ovqatlar, narx in ovqat.items():
#     print(f"{ovqatlar}:{narx}")
#3
# gruh=["asad","humoyun","behruz","raxmatulla","asad","nuriddin","og'abek"]
# baholanganlar={}
# while gruh:
#     gruhlar=gruh.pop()
#     baho=input(f"{gruhlar.title()}ning bahosini kiriting:")
#     print(f"{gruhlar.title()}-baholandi")
#     baholanganlar[gruhlar]=int(baho)
#4
