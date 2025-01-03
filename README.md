body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background: url('images/background.jpg') no-repeat center center/cover;
    color: #fff;
}

/* Navigation */
header nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 50px;
    background: rgba(0, 0, 0, 0.7);
}

header nav .logo {
    font-size: 24px;
    font-weight: bold;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Hero Section */
#hero {
    text-align: center;
    padding: 100px 0;
    background: rgba(0, 0, 0, 0.6);
}

#hero h1 {
    font-size: 48px;
}

#hero .cta-btn {
    margin-top: 20px;
    padding: 10px 20px;
    background: #ff9800;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Site Grid */
.site-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 50px;
}

.site-card {
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
    text-align: center;
    border-radius: 8px;
    width: 200px;
}
