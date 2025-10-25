# محاكاة هجوم Brute Force (تجربة جميع الاحتمالات لكلمة مرور بسيطة)
import itertools

password = "1234"  # كلمة المرور الحقيقية
attempts = 0

# توليد جميع الاحتمالات الممكنة لأرقام من 4 خانات
for guess in itertools.product("0123456789", repeat=4):
    attempts += 1
    guess_password = "".join(guess)
    if guess_password == password:
        print(f"تم اكتشاف كلمة المرور: {guess_password} بعد {attempts} محاولة")
        break