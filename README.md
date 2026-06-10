<LinearLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    android:padding="20dp"
    android:gravity="center_horizontal">

    <!-- Titre de l'écran -->
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="NativeCompute"
        android:textSize="26sp"
        android:textStyle="bold"
        android:textColor="#1A237E"
        android:gravity="center"
        android:paddingBottom="6dp" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Fonctions C++ via JNI"
        android:textSize="14sp"
        android:textColor="#5C6BC0"
        android:gravity="center"
        android:paddingBottom="24dp" />

    <!-- Carte 1 : Greeting -->
    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="16dp"
        app:cardCornerRadius="12dp"
        app:cardElevation="4dp"
        xmlns:app="http://schemas.android.com/apk/res-auto">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:padding="16dp">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="BIENVENUE"
                android:textSize="11sp"
                android:textColor="#9E9E9E"
                android:textStyle="bold"
                android:letterSpacing="0.1"
                android:paddingBottom="6dp" />

            <TextView
                android:id="@+id/labelGreeting"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Chargement..."
                android:textSize="17sp"
                android:textColor="#212121" />
        </LinearLayout>
    </androidx.cardview.widget.CardView>

    <!-- Carte 2 : Puissance -->
    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="16dp"
        app:cardCornerRadius="12dp"
        app:cardElevation="4dp"
        xmlns:app="http://schemas.android.com/apk/res-auto">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:padding="16dp">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="EXPONENTIATION (base^exp)"
                android:textSize="11sp"
                android:textColor="#9E9E9E"
                android:textStyle="bold"
                android:letterSpacing="0.1"
                android:paddingBottom="6dp" />

            <TextView
                android:id="@+id/labelPower"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Calcul en cours..."
                android:textSize="17sp"
                android:textColor="#212121" />
        </LinearLayout>
    </androidx.cardview.widget.CardView>

    <!-- Carte 3 : Miroir -->
    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="16dp"
        app:cardCornerRadius="12dp"
        app:cardElevation="4dp"
        xmlns:app="http://schemas.android.com/apk/res-auto">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:padding="16dp">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="MIROIR DE TEXTE"
                android:textSize="11sp"
                android:textColor="#9E9E9E"
                android:textStyle="bold"
                android:letterSpacing="0.1"
                android:paddingBottom="6dp" />

            <TextView
                android:id="@+id/labelMirror"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Traitement..."
                android:textSize="17sp"
                android:textColor="#212121" />
        </LinearLayout>
    </androidx.cardview.widget.CardView>

    <!-- Carte 4 : Moyenne -->
    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="16dp"
        app:cardCornerRadius="12dp"
        app:cardElevation="4dp"
        xmlns:app="http://schemas.android.com/apk/res-auto">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:padding="16dp">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="MOYENNE DU TABLEAU"
                android:textSize="11sp"
                android:textColor="#9E9E9E"
                android:textStyle="bold"
                android:letterSpacing="0.1"
                android:paddingBottom="6dp" />

            <TextView
                android:id="@+id/labelAverage"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Calcul..."
                android:textSize="17sp"
                android:textColor="#212121" />
        </LinearLayout>
    </androidx.cardview.widget.CardView>

</LinearLayout>
