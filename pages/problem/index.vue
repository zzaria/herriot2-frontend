<template>
    <div class="flex flex-col md:flex-row">
        <Title>Problems</Title>
        <div class="xl:mr-5 md:w-1/4">
            <div class="bg-frostedglass-600 dark:bg-glass-600 p-2.5 sticky top-14">
                <problemFilter />
            </div>
        </div>
        <div class="bg-frostedglass-600 dark:bg-glass-600 xl:ml-5 p-2.5 grow">
            <problemList />
        </div>
    </div>
</template>

