# Dashboard.krisha

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Layout</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <div class="flex h-screen">
        <!-- Sidebar -->
        <aside class="w-64 bg-gray-800 text-white p-5 hidden md:block">
            <h2 class="text-2xl font-bold">Dashboard</h2>
            <nav class="mt-5">
                <ul>
                    <li class="py-2"><a href="#" class="block hover:bg-gray-700 p-2 rounded">Home</a></li>
                    <li class="py-2"><a href="#" class="block hover:bg-gray-700 p-2 rounded">Profile</a></li>
                    <li class="py-2"><a href="#" class="block hover:bg-gray-700 p-2 rounded">Settings</a></li>
                </ul>
            </nav>
        </aside>

        <!-- Main Content -->
        <div class="flex-1 flex flex-col">
            <!-- Navbar -->
            <header class="bg-white shadow p-4 flex justify-between items-center">
                <h1 class="text-xl font-semibold">Dashboard</h1>
                <button class="md:hidden bg-gray-800 text-white px-4 py-2 rounded">Menu</button>
            </header>

            <!-- Dashboard Content -->
            <main class="p-6">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow">
                        <h3 class="text-lg font-bold">Total Users</h3>
                        <p class="text-2xl">1,234</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow">
                        <h3 class="text-lg font-bold">Revenue</h3>
                        <p class="text-2xl">$12,345</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow">
                        <h3 class="text-lg font-bold">Orders</h3>
                        <p class="text-2xl">567</p>
                    </div>
                </div>
            </main>
        </div>
    </div>
</body>
</html>
