# 📱 TP Android – HelloToast

## 🎯 Objectif du TP
Le projet **HelloToast** a pour but d’apprendre à manipuler les **composants graphiques Android** (`TextView`, `Button`, `Toast`) et à gérer les **événements de clics**.  
Il s’agit d’une introduction à la programmation d’interfaces avec **Android Studio** en Java.

---

## 🧩 Structure du projet
<img width="596" height="714" alt="image" src="https://github.com/user-attachments/assets/7c0cfe8d-058d-471c-9bae-6f0a62737fd1" />

---

## 🖥️ Interface utilisateur (activity_main.xml)


<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    android:gravity="center_horizontal">

    <TextView
        android:id="@+id/text_count"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="0"
        android:textSize="40sp"
        android:layout_marginBottom="20dp" />

    <Button
        android:id="@+id/button_toast"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Say Hello"
        android:layout_marginBottom="10dp" />

    <Button
        android:id="@+id/button_count"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Count" />
</LinearLayout>

https://github.com/user-attachments/assets/9cef3d3d-c84c-4bd3-a217-814f25004966

![WhatsApp Image 2025-11-11 à 19 28 46_3e7806e3](https://github.com/user-attachments/assets/7ad77c3b-11cc-452c-b01a-b04f655dd825)
